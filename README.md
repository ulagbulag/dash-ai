# DASH AI Templates

## Requirements

* [OpenARK](https://github.com/ulagbulag/OpenARK/)
* [OpenARK DASH](https://github.com/ulagbulag/OpenARK/)

## Deployment

```bash
./deploy.sh
```

## Examples

### Create a Job

```bash
dash create \
    --function "pytorch" \
    --namespace "dash-ai" \
    --value "/gpus/3" \
    --value "/ip/10.20.30.40" \
    --value "/user/name/my-user" \
    --value "/user/password/my-password"
```

### Delete a Job

```bash
dash delete \
    --function "pytorch" \
    --namespace "dash-ai" \
    --value "/gpus/3" \
    --value "/ip/10.20.30.40" \
    --value "/user/name/my-user" \
    --value "/user/password/my-password"
```

### Check a Job

```bash
dash exists \
    --function "pytorch" \
    --namespace "dash-ai" \
    --value "/gpus/3" \
    --value "/ip/10.20.30.40" \
    --value "/user/name/my-user" \
    --value "/user/password/my-password"
```

### Restart a Job

```bash
dash restart \
    --function "pytorch" \
    --namespace "dash-ai" \
    --value "/gpus/3" \
    --value "/ip/10.20.30.40" \
    --value "/user/name/my-user" \
    --value "/user/password/my-password"
```
