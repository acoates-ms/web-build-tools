[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfiguration](./rush-lib.rushconfiguration.md) &gt; [npmTmpFolder](./rush-lib.rushconfiguration.npmtmpfolder.md)

# RushConfiguration.npmTmpFolder property

The local folder where npm's temporary files will be written during installation. Rush does not rely on the global default folder, because it may be on a different hard disk.

Example: "C:\\MyRepo\\common\\temp\\npm-tmp"

**Signature:**
```javascript
npmTmpFolder: string
```