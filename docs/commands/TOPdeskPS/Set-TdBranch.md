---
external help file: TOPdeskPS-help.xml
Module Name: TOPdeskPS
online version:
schema: 2.0.0
---

# Set-TdBranch

## SYNOPSIS
update a branch by id

## SYNTAX

```
Set-TdBranch -BranchId <Object> [-Name <String>] [-Specification <String>] [-ClientReferenceNumber <String>]
 [-Phone <String>] [-fax <String>] [-Email <String>] [-Website <String>] [-BranchType <String>]
 [-HeadBranchId <Object>] [-Address <Hashtable>] [-PostalAddress <Hashtable>] [-OptionalFields1 <Hashtable>]
 [-OptionalFields2 <Hashtable>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
update branch

## EXAMPLES

### EXAMPLE 1
```
Set-TdBranch -BranchId (Get-TdBranch -Name 'Test Branch').id -Phone '555-555-5555'
```

Updates the Test Branch phone number.

## PARAMETERS

### -BranchId
{{Fill BranchId Description}}

```yaml
Type: Object
Parameter Sets: (All)
Aliases: Id

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Name of the branch

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Specification
Branch specification

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClientReferenceNumber
Client Reference Number

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Phone
Phone Number

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -fax
Fax Number

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Email
email address

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Website
Website URL

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BranchType
Define the type of branch.
Optional values: 'independentBranch', 'headBranch', 'hasAHeadBranch'

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HeadBranchId
ID of head branch

```yaml
Type: Object
Parameter Sets: (All)
Aliases: HeadBranch

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Address
Hashtable containing address values

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PostalAddress
Hashtable containing postal address values

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OptionalFields1
{{Fill OptionalFields1 Description}}

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OptionalFields2
{{Fill OptionalFields2 Description}}

```yaml
Type: Hashtable
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS