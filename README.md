
[TESTS]: ./TESTS.md
[Invoke-PowerShell.ps1]: https://www.powershellgallery.com/packages/Invoke-PowerShell

*PowerShellTraps* is a collection of some PowerShell traps and oddities shown
by demo scripts, workarounds, and automated tests. On invoking scripts change
to their directory. See also [TESTS]. Some scripts require
[Invoke-PowerShell.ps1].

---

<!--Generated-->
- [Basic](./Basic)
    - [And-and-or-have-same-precedence](./Basic/And-and-or-have-same-precedence)
    - [Automatic-variables](./Basic/Automatic-variables)
    - [Break-and-Continue-with-not-matching-label](./Basic/Break-and-Continue-with-not-matching-label)
    - [Break-and-Continue-without-loop](./Basic/Break-and-Continue-without-loop)
    - [Collection-property-enumeration](./Basic/Collection-property-enumeration)
    - [Comparison-operators-with-collections](./Basic/Comparison-operators-with-collections)
    - [Compound-assignment-operators](./Basic/Compound-assignment-operators)
    - [Count-and-Length](./Basic/Count-and-Length)
        - [Mixed-objects](./Basic/Count-and-Length/Mixed-objects)
        - [PSCustomObject](./Basic/Count-and-Length/PSCustomObject)
        - [Strict-Mode](./Basic/Count-and-Length/Strict-Mode)
    - [Different-kinds-of-null](./Basic/Different-kinds-of-null)
    - [Double-quoted-string](./Basic/Double-quoted-string)
    - [DynamicParam](./Basic/DynamicParam)
        - [Dynamic-switch-parameter](./Basic/DynamicParam/Dynamic-switch-parameter)
        - [ExpectingInput-is-false](./Basic/DynamicParam/ExpectingInput-is-false)
    - [Enums-evaluated-to-true](./Basic/Enums-evaluated-to-true)
    - [Errors-of-unusual-type](./Basic/Errors-of-unusual-type)
    - [FormatEnumerationLimit](./Basic/FormatEnumerationLimit)
    - [Function-invoked-like-method](./Basic/Function-invoked-like-method)
    - [Invocation-with-odd-paths](./Basic/Invocation-with-odd-paths)
    - [LastExitCode](./Basic/LastExitCode)
    - [Local-ActionPreference](./Basic/Local-ActionPreference)
    - [Misleading-error-location](./Basic/Misleading-error-location)
    - [Missing-ternary-operator](./Basic/Missing-ternary-operator)
    - [Negative-number-literal-argument](./Basic/Negative-number-literal-argument)
    - [Null-converted-to-empty-string](./Basic/Null-converted-to-empty-string)
    - [Number-of-returned-objects](./Basic/Number-of-returned-objects)
    - [Operators-match-notmatch-and-matches](./Basic/Operators-match-notmatch-and-matches)
    - [Operators-with-equal-precedence](./Basic/Operators-with-equal-precedence)
    - [Properties-of-IDictionary](./Basic/Properties-of-IDictionary)
    - [Properties-of-XmlNode](./Basic/Properties-of-XmlNode)
    - [Provider-specific-Filter](./Basic/Provider-specific-Filter)
    - [PSCustomObject](./Basic/PSCustomObject)
    - [PSReference](./Basic/PSReference)
    - [Requires](./Basic/Requires)
    - [RunspacePool](./Basic/RunspacePool)
    - [Statements-are-not-expressions](./Basic/Statements-are-not-expressions)
    - [Strict-mode-ErrorRecord-formatting](./Basic/Strict-mode-ErrorRecord-formatting)
    - [String-equality-operators](./Basic/String-equality-operators)
    - [Switch-is-a-looping-construct](./Basic/Switch-is-a-looping-construct)
    - [Tempting-wrong-operators](./Basic/Tempting-wrong-operators)
    - [ThrowTerminatingError](./Basic/ThrowTerminatingError)
        - [Catch-is-not-called](./Basic/ThrowTerminatingError/Catch-is-not-called)
        - [Not-true-terminating](./Basic/ThrowTerminatingError/Not-true-terminating)
    - [Too-simple-function-names](./Basic/Too-simple-function-names)
    - [Trap-creates-a-new-scope](./Basic/Trap-creates-a-new-scope)
    - [Trap-with-continue](./Basic/Trap-with-continue)
    - [Trap-with-no-break-or-continue](./Basic/Trap-with-no-break-or-continue)
    - [Try-and-trap-catch-terminating-errors](./Basic/Try-and-trap-catch-terminating-errors)
    - [Unexpected-output](./Basic/Unexpected-output)
    - [Unexpected-overloaded-method](./Basic/Unexpected-overloaded-method)
    - [Unrolled-collections](./Basic/Unrolled-collections)
    - [v5-Method-New](./Basic/v5-Method-New)
    - [ValidateScript-attribute](./Basic/ValidateScript-attribute)
    - [ValueFromRemainingArguments](./Basic/ValueFromRemainingArguments)
    - [When-Process-block-is-called](./Basic/When-Process-block-is-called)
    - [WildcardPattern](./Basic/WildcardPattern)
- [Class](./Class)
    - [Cannot-derive-from-dot-sourced](./Class/Cannot-derive-from-dot-sourced)
    - [Identical-scriptblocks-issue](./Class/Identical-scriptblocks-issue)
    - [Method-cannot-see-created-variable](./Class/Method-cannot-see-created-variable)
    - [Parser-fails-on-custom-type](./Class/Parser-fails-on-custom-type)
- [Clixml](./Clixml)
    - [Cannot-write-to-hidden-files](./Clixml/Cannot-write-to-hidden-files)
    - [Hashtable-case-sensitivity](./Clixml/Hashtable-case-sensitivity)
    - [OrderedDictionary-becomes-Hashtable](./Clixml/OrderedDictionary-becomes-Hashtable)
    - [ScriptBlock-becomes-String](./Clixml/ScriptBlock-becomes-String)
    - [v2-no-LiteralPath](./Clixml/v2-no-LiteralPath)
- [Cmdlets](./Cmdlets)
    - [ConvertFrom-Csv](./Cmdlets/ConvertFrom-Csv)
        - [Partial-comment-support](./Cmdlets/ConvertFrom-Csv/Partial-comment-support)
    - [ConvertFrom-Json](./Cmdlets/ConvertFrom-Json)
        - [Not-unrolled-result](./Cmdlets/ConvertFrom-Json/Not-unrolled-result)
        - [Piping-content](./Cmdlets/ConvertFrom-Json/Piping-content)
        - [v6-long-integers](./Cmdlets/ConvertFrom-Json/v6-long-integers)
    - [ConvertTo-Json](./Cmdlets/ConvertTo-Json)
        - [Array-as-PSObject](./Cmdlets/ConvertTo-Json/Array-as-PSObject)
        - [v3-Without-Compress](./Cmdlets/ConvertTo-Json/v3-Without-Compress)
    - [Copy-Item](./Cmdlets/Copy-Item)
        - [Exclude-and-Recurse](./Cmdlets/Copy-Item/Exclude-and-Recurse)
        - [Inconsistent-destination](./Cmdlets/Copy-Item/Inconsistent-destination)
    - [ForEach-Object](./Cmdlets/ForEach-Object)
    - [Get-ChildItem](./Cmdlets/Get-ChildItem)
        - [Different-FileInfo-ToString](./Cmdlets/Get-ChildItem/Different-FileInfo-ToString)
        - [Directory-with-backticks](./Cmdlets/Get-ChildItem/Directory-with-backticks)
        - [Directory-with-brackets](./Cmdlets/Get-ChildItem/Directory-with-brackets)
        - [Missing-path-and-Recurse](./Cmdlets/Get-ChildItem/Missing-path-and-Recurse)
        - [v5-LiteralPath-Recurse-ignores-Include](./Cmdlets/Get-ChildItem/v5-LiteralPath-Recurse-ignores-Include)
    - [Get-Event](./Cmdlets/Get-Event)
        - [v2-4-Erratic-failure](./Cmdlets/Get-Event/v2-4-Erratic-failure)
    - [Get-Item](./Cmdlets/Get-Item)
        - [Certificate-provider](./Cmdlets/Get-Item/Certificate-provider)
        - [Directory-with-brackets](./Cmdlets/Get-Item/Directory-with-brackets)
    - [Get-ItemPropertyValue](./Cmdlets/Get-ItemPropertyValue)
        - [ErrorAction-ignored](./Cmdlets/Get-ItemPropertyValue/ErrorAction-ignored)
    - [Get-Unique](./Cmdlets/Get-Unique)
    - [Get-WmiObject](./Cmdlets/Get-WmiObject)
        - [Strict-mode-Latest](./Cmdlets/Get-WmiObject/Strict-mode-Latest)
    - [Group-Object](./Cmdlets/Group-Object)
        - [AsHashTable](./Cmdlets/Group-Object/AsHashTable)
        - [Expression-with-no-value](./Cmdlets/Group-Object/Expression-with-no-value)
    - [Import-Csv](./Cmdlets/Import-Csv)
    - [Import-Module](./Cmdlets/Import-Module)
        - [Non-terminating-error](./Cmdlets/Import-Module/Non-terminating-error)
    - [Invoke-Expression](./Cmdlets/Invoke-Expression)
        - [ErrorAction](./Cmdlets/Invoke-Expression/ErrorAction)
    - [Invoke-RestMethod](./Cmdlets/Invoke-RestMethod)
        - [Not-unrolled-result](./Cmdlets/Invoke-RestMethod/Not-unrolled-result)
    - [Join-Path](./Cmdlets/Join-Path)
    - [Read-Host](./Cmdlets/Read-Host)
        - [v5-Output-before-Read-Host](./Cmdlets/Read-Host/v5-Output-before-Read-Host)
    - [Remove-Item](./Cmdlets/Remove-Item)
        - [Directory-with-brackets](./Cmdlets/Remove-Item/Directory-with-brackets)
        - [Exclude-may-be-ignored](./Cmdlets/Remove-Item/Exclude-may-be-ignored)
    - [Remove-ItemProperty](./Cmdlets/Remove-ItemProperty)
    - [Rename-Item](./Cmdlets/Rename-Item)
        - [v2-no-LiteralPath](./Cmdlets/Rename-Item/v2-no-LiteralPath)
    - [Resolve-Path](./Cmdlets/Resolve-Path)
        - [Wildcards-miss-hidden-items](./Cmdlets/Resolve-Path/Wildcards-miss-hidden-items)
    - [Select-Xml](./Cmdlets/Select-Xml)
        - [Content-as-stream](./Cmdlets/Select-Xml/Content-as-stream)
    - [Set-Content](./Cmdlets/Set-Content)
        - [Directory-with-brackets](./Cmdlets/Set-Content/Directory-with-brackets)
        - [Unexpected-output-location](./Cmdlets/Set-Content/Unexpected-output-location)
    - [Split-Path](./Cmdlets/Split-Path)
    - [Start-Process](./Cmdlets/Start-Process)
    - [Start-Transcript](./Cmdlets/Start-Transcript)
        - [v5-Unexpected-stop](./Cmdlets/Start-Transcript/v5-Unexpected-stop)
    - [Test-Path](./Cmdlets/Test-Path)
        - [Incorrect-in-odd-location](./Cmdlets/Test-Path/Incorrect-in-odd-location)
        - [Wildcards-miss-hidden-items](./Cmdlets/Test-Path/Wildcards-miss-hidden-items)
    - [Wait-Process](./Cmdlets/Wait-Process)
    - [Where-Object](./Cmdlets/Where-Object)
    - [Write-Debug](./Cmdlets/Write-Debug)
    - [Write-Progress](./Cmdlets/Write-Progress)
- [Module](./Module)
    - [Conflict-with-aliases](./Module/Conflict-with-aliases)
    - [Function-parent-scope](./Module/Function-parent-scope)
    - [Not-found-function](./Module/Not-found-function)
    - [Not-found-function-2](./Module/Not-found-function-2)
    - [Not-found-variable](./Module/Not-found-variable)
    - [Script-block-scope](./Module/Script-block-scope)
    - [Strict-mode-is-not-propagated](./Module/Strict-mode-is-not-propagated)
    - [v2-Manifest-RootModule-is-not-supported](./Module/v2-Manifest-RootModule-is-not-supported)
- [PowerShell.exe](./PowerShell.exe)
    - [Exit-code-0-with-Command-syntax-error](./PowerShell.exe/Exit-code-0-with-Command-syntax-error)
    - [Exit-code-0-with-File-script-error](./PowerShell.exe/Exit-code-0-with-File-script-error)
    - [Exit-code-5-with-File-1-with-Command](./PowerShell.exe/Exit-code-5-with-File-1-with-Command)
    - [Exit-code-depends](./PowerShell.exe/Exit-code-depends)
    - [Global-and-script-scope](./PowerShell.exe/Global-and-script-scope)
    - [Not-current-version](./PowerShell.exe/Not-current-version)
    - [Positional-Command-File](./PowerShell.exe/Positional-Command-File)
    - [Switch-parameter-with-value](./PowerShell.exe/Switch-parameter-with-value)
    - [Unexpected-start-location](./PowerShell.exe/Unexpected-start-location)
    - [v3-Interactive-issues](./PowerShell.exe/v3-Interactive-issues)
    - [Version-parameter](./PowerShell.exe/Version-parameter)
    - [Version-scriptblock-host-problem](./PowerShell.exe/Version-scriptblock-host-problem)

---
