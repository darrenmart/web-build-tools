[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfiguration](./rush-lib.rushconfiguration.md) &gt; [projectFolderMinDepth](./rush-lib.rushconfiguration.projectfoldermindepth.md)

# RushConfiguration.projectFolderMinDepth property

The minimum allowable folder depth for the projectFolder field in the rush.json file. This setting provides a way for repository maintainers to discourage nesting of project folders that makes the directory tree more difficult to navigate. The default value is 2, which implements a standard 2-level hierarchy of &lt;categoryFolder&gt;/&lt;projectFolder&gt;/package.json.

**Signature:**
```javascript
projectFolderMinDepth: number
```