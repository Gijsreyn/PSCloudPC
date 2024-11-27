---
document type: cmdlet
external help file: PSCloudPC-Help.xml
HelpUri: ''
Locale: en-NL
Module Name: PSCloudPC
ms.date: 11/27/2024
PlatyPS schema version: 2024-05-01
title: Import-CPCProvisioningPolicy
---

# Import-CPCProvisioningPolicy

## SYNOPSIS

Imports a Provisioning Policy from a JSON File

## SYNTAX

### Name

```
Import-CPCProvisioningPolicy -Inputfile <string> [<CommonParameters>]
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

The function will import a Provisioning Policy from a JSON File

## EXAMPLES

### EXAMPLE 1

Import-CPCProvisioningPolicy -Inputfile "C:\Temp\AzureADJoinPolicy.json"

## PARAMETERS

### -Inputfile

Enter the path to the JSON File

```yaml
Type: System.String
DefaultValue: ''
SupportsWildcards: false
ParameterValue: []
Aliases: []
ParameterSets:
- Name: Name
  Position: Named
  IsRequired: true
  ValueFromPipeline: false
  ValueFromPipelineByPropertyName: false
  ValueFromRemainingArguments: false
DontShow: false
AcceptedValues: []
HelpMessage: ''
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable,
-InformationAction, -InformationVariable, -OutBuffer, -OutVariable, -PipelineVariable,
-ProgressAction, -Verbose, -WarningAction, and -WarningVariable. For more information, see
[about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

{{ Fill in the related links here }}
