# jQuery Mu Image Resize

Mu Image Resize is a jQuery Plugin to resize and crop the images with specific class names.
Mu Image Resize 是用來進行前端圖片自動縮放與裁切的外掛，只要給定圖片的class名稱、期望寬度、期望高度，它就會在圖片載入(load)完畢後，依比例縮放圖片，並且裁切出置中區域作為縮圖的縮示。

## Change Log

1.0.4 fix issue: if plugin cannot get image width & height in load event, just set the given width & height.

1.0.3 fix issue: fix IE cannot get width/height correctly[workaround].

1.0.2 fix issue: image width:auto cannot get value correctly.

1.0.1 initial