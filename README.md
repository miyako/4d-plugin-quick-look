4d-plugin-quick-look
====================

Create Quick Look thumbnail, launch Quick Look preview.

##Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|🆗|🆗|🚫|🚫|

Commands
---

```c
// --- Quick Look
QL_REQUEST_PREVIEW
QL_Get_file_thumbnail
```

Eaxmples
---

```
  //creates a preview image (normally TIFF) of size
$image:=QL Get file thumbnail ($filePath;$width;$height)
```

```
QL REQUEST PREVIEW ($filePath)
```
