---
external help file: passwordstate-management-help.xml
Module Name: passwordstate-management
online version:
schema: 2.0.0
---

# Remove-PasswordStatePassword

## SYNOPSIS
Deletes a password state entry.

## SYNTAX

```
Remove-PasswordStatePassword [[-PasswordID] <Object>] [-SendToRecycleBin] [<CommonParameters>]
```

## DESCRIPTION
Deletes a password state entry.

## EXAMPLES

### EXAMPLE 1
```
Remove-PasswordStatePassword -PasswordID 5 -sendtorecyclebin
```

Returns the test user object including password.

## PARAMETERS

### -PasswordID
ID value of the entry to delete.
Int32 value

```yaml
Type: Object
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -SendToRecycleBin
Send the password to the recyclebin or permenant delete.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### PasswordID - ID of the Password entry (Integer)
SendtoRecyclebin - Optionally soft delete to the reyclebin

## OUTPUTS

### Returns the Object from the API as a powershell object.

## NOTES
Daryl Newsholme 2018

## RELATED LINKS