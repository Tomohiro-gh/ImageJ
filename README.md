# ImageJ
ImageJ macro codes


### BioFormatからのfile open (スペースを含む場合）
  cf) https://yasuo-ssi.hatenablog.com/entry/2020/11/25/003000
```java
IJ.run("Bio-Formats Importer", "open=\'"+ folder + filename + "\' autoscale ...
```
