# PowerShellScripts
Some PowerShell scipts I wrote, that could turn out being useful to others, too.

| Function | Location | Synopsis | Related Blog Post | Full Documentation |
| --- | --- | --- | --- | --- |
| Get-ESSearchResult1 | Binary Wrapper\Get-ESSearchResult.ps1 |PowerShell wrapper around Everything search command line (es.exe). | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-ESSearchResult1.md) |
| SilverSearcher | Binary Wrapper\SilverSearcher.ps1 |PowerShell wrapper around silver searcher (ag.exe) Recursively search for PATTERN in PATH. Like grep or ack, but faster. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/SilverSearcher.md) |
| Get-ChangeLog | Data Wrangling\Get-ChangeLog.ps1 |Comparing two objects or .csv files column by column. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-ChangeLog.md) |
| Sort-CustomList | Data Wrangling\Sort-CustomList.ps1 |Sort data using a custom list in PowerShell. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Sort-CustomList.md) |
| Update-Content | Data Wrangling\Update-Content.ps1 |Insert text on a new line after the line matching the StartPattern or replace text between start- and end Pattern within a file |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Update-Content.md) |
| Compare-File | Extend Builtin\Compare-File.ps1 |A wrapper and extension for the built-in Compare-Object cmdlet to compare two txt based files and receive a side-by-side comparison (including Line numbes). |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Compare-File.md) |
| Get-Choice | Extend Builtin\Get-Choice.ps1 |An alternative to the built-in PromptForChoice providing a consistent UI across different hosts. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-Choice.md) |
| Get-Range | Extend Builtin\Get-Range.ps1 |Function to retrieve a continuous or stepwise Range of integers,decimals,dates,month names, day names or chars. Simulating Haskell`s Range operator | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-Range.md) |
| Join-Tables | Extend Builtin\Join-Tables.ps1 |Function to join tables based on one or more common columns with an option to summarize (aggregate) joined columns. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Join-Tables.md) |
| Select-ObjectX | Extend Builtin\Simplified-Select.ps1 |Proxy function for Select-Object providing easier syntax for calculated properties. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Select-ObjectX.md) |
| WhereEx | Extend Builtin\WhereEx.ps1 |POC for a simplified Where-Object with multiple conditions on the same property for PowerShell. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/WhereEx.md) |
| Add-FormatTableView | Format Output\Add-FormatTableView.ps1 |Function to add a Format Table View for a type | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Add-FormatTableView.md) |
| Add-PropertySet | Format Output\Add-PropertySet.ps1 |Function to create property sets | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Add-PropertySet.md) |
| ConvertTo-HtmlConditionalFormat | Format Output\ConvertTo-HtmlConditionalFormat.ps1 |Function to convert PowerShell objects into an HTML table with the option to format individual table cells based on property values using CSS selectors. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/ConvertTo-HtmlConditionalFormat.md) |
| Get-FormatView | Format Output\Get-FormatView.ps1 |Function to get the format views for a particular type. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-FormatView.md) |
| Out-ConditionalColor | Format Output\Out-ConditionalColor.ps1 |Filter to conditionally format PowerShell output within the PowerShell console. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Out-ConditionalColor.md) |
| Out-ConditionalColorProperties | Format Output\Out-ConditionalColorProperties.ps1 |Filter to conditionally format property values within PowerShell output on the console. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Out-ConditionalColorProperties.md) |
| Out-Diff | Format Output\Out-Diff.ps1 |Generate html diff from git diff output using diff2html. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Out-Diff.md) |
| 8Queens | Programming Exercises\8 Queens.ps1 |PowerShell solution for a classical programming exercise. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/8Queens.md) |
| GenerateSolveMaze | Programming Exercises\GenerateSolveMaze.ps1 |Function to generate a GUI (Windows forms) to build and solve random mazes |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/GenerateSolveMaze.md) |
| TowerOfHanoi | Programming Exercises\TowerOfHanoi.ps1 |PowerShell solution to the Tower of Hanoi problem (http://en.wikipedia.org/wiki/Tower_of_Hanoi) using recursion. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/TowerOfHanoi.md) |
| Add-PowerShellContextMenu | Utils\Add-PowerShellContextMenu.ps1 |Function to create context menu entries in order to invoke PowerShell | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Add-PowerShellContextMenu.md) |
| Add-ScriptHelpISEAddOn | Utils\Add-ScriptHelpISEAddOn.ps1 |Function to create an ISE Add-On that will generate comment based help for functions. The functions requires the Show-UI module. | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Add-ScriptHelpISEAddOn.md) |
| ConvertFrom-ExcelClipboard | Utils\ConvertFrom-ExcelClipboard.ps1 |Convert copied range from excel to an array of PSObjects | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/ConvertFrom-ExcelClipboard.md) |
| ConvertFrom-HtmlToText | Utils\ConvertFrom-HtmlToText.ps1 |Extract the text out of a HTML string |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/ConvertFrom-HtmlToText.md) |
| ConvertTo-PSFunction | Utils\ConvertTo-PSFunction.ps1 |Function to "convert" legacy command line commands to PowerShell functions |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/ConvertTo-PSFunction.md) |
| Delete-ComputerRestorePoint | Utils\Delete-ComputerRestorePoint.ps1 |Function to Delete Windows System Restore points |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Delete-ComputerRestorePoint.md) |
| ForeachFor2 | Utils\ForeachFor2.ps1 |Function to step through two series of values in two collections and run commands against them. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/ForeachFor2.md) |
| Get-FileAndExtract | Utils\Get-FileAndExtract.ps1 |Function to download and extract files. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-FileAndExtract.md) |
| Get-Uninstaller | Utils\Get-Uninstaller.ps1 |Function to get the uninstaller for installed software via registry (PowerShell v4 and <) or Get-Package) | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-Uninstaller.md) |
| Get-WIFIPassword | Utils\Get-WIFIPassword.ps1 |Get the Wifi password of stored networks using netsh. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-WIFIPassword.md) |
| Invoke-HTMLPesterReport | Utils\Invoke-HTMLPesterReport.ps1 |Generate HTML report for Pester test results using ReportUnit.exe | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Invoke-HTMLPesterReport.md) |
| Migrate-ScheduledTask | Utils\Migrate-ScheduledTask.ps1 |Script to migrate scheduled tasks from Windows XP/Server 2003 to Windows 7/Server 2008 task scheduler |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Migrate-ScheduledTask.md) |
| Monitor-Folder | Utils\Monitor-Folder.ps1 |Monitors a folder for changes using non-persistent asynchronous events |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Monitor-Folder.md) |
| Open-Registry | Utils\Open-Registry.ps1 |Open the regedit at the specified path similar to sysinternals regjump. |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Open-Registry.md) |
| Restart-Process | Utils\Restart-Process.ps1 |Function to restart process(es) | [Link]() | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Restart-Process.md) |
| Get-FunctionFromScript | PowerShellScripts\Generate-ScriptMarkdownHelp.ps1 |Gets the functions and filters declared within a script block or a file |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Get-FunctionFromScript.md) |
| Generate-ScriptMarkdownHelp | PowerShellScripts\Generate-ScriptMarkdownHelp.ps1 |The function that generated the Markdown help in this repository. (see Example for usage).  Generates markdown help for Github for each function containing comment based help (Description not empty) within a folder recursively and a summary table for the main README.md |  | [Link](https://github.com/DBremen/PowerShellScripts/blob/master/docs/Generate-ScriptMarkdownHelp.md) |
