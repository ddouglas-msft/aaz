# [Command] _afd rule show_

Get an existing delivery rule within a rule set.

## Versions

### [2023-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jZG4vcHJvZmlsZXMve30vcnVsZXNldHMve30vcnVsZXMve30=/2023-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.cdn/profiles/{}/rulesets/{}/rules/{} 2023-05-01 -->

#### examples

- show details of the delivery rule with name rule1.
    ```bash
        afd rule show -g group --rule-set-name ruleSetName --profile-name profile --rule-name rule1
    ```
