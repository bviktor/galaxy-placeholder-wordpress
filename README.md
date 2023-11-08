# bviktor.namespace

## Synopsys

This placeholder role is here to tell you that you need to switch namespace from `bviktor` to `noobient`.

## Parameters

N/A

## Examples

```
# requirements
sed -i 's/bviktor\./noobient\./g' requirements.yml
sed -i 's/bviktor\./noobient\./g' meta/requirements.yml
# include_role's
find . -type f -not -path '*/\.*' -exec sed -i 's/name: bviktor\./name: noobient\./g' {} +
```

## Return Values

N/A

## Support

N/A
