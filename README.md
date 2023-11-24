## json file
### scroll_or_stages_version.json
```json
{
    "scroll_version": "HoS_v6.0",
    "stages_version": "744/ARMS_2023_12"
}
```

#### Parameters
`scroll_version`
Specifies the Scroll Versions target version in which the changes will be visible. This can be for example 'HoS_v2.0'

`stages_version`
Stages process version including workspace id, e.g. 744/ARMS_2022_01

### stages_white_list.json
```json
{
    "workspace_id_white_list": [
        "744"
    ]
}
```

#### Parameters
`workspace_id_white_list`
Allow updating links in the Confluence space related to these IDs.
