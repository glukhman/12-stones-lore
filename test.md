> [!NOTE]
> Useful information that users should know, even when skimming content.


There is no way to do so. Either use an HTML table, or put the same text on several cells.

like this:

| Can Reorder <td colspan=3> 2nd operation ||||
| :---: | --- |-|-|
|1st operation|Normal Load <br/>Normal Store| Volatile Load <br/>MonitorEnter|Volatile Store<br/> MonitorExit|
|Normal Load <br/> Normal Store| | | No|
|Volatile Load <br/> MonitorEnter| No|No|No|
|Volatile store <br/> MonitorExit| | No|No|

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
