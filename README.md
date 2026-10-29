# LiteThumbs — releases

Miniaturas no Explorer do Windows para PSD, SVG, AVIF, HEIC, JPEG XL, RAW de câmera, DDS, SHD/SHM e outros formatos.

Este repositório só guarda os pacotes. Baixe o zip da [última release](../../releases/latest), extraia e rode:

```powershell
powershell -ExecutionPolicy Bypass -File .\install.ps1
```

Depois de instalado, o configurador (`LiteThumbsConfig.exe`) avisa quando há versão nova e se atualiza sozinho. Os zips são assinados (Ed25519) e o configurador só instala os que conferem.
