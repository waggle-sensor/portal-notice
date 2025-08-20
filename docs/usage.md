# Documentation

## Usage

The Sage Portal pulls from [here](https://raw.githubusercontent.com/waggle-sensor/portal-notice/refs/heads/main/notice.json) which corresponds to [notice.json](https://github.com/waggle-sensor/portal-notice/blob/main/notice.json)

Update [notice.json](https://github.com/waggle-sensor/portal-notice/blob/main/notice.json) to add or remove a banner.


### Format

```typescript
{
  message: string
  severity?: 'info' | 'warning' | 'error' | 'success' // defaults to 'info'
}
```

### Examples

#### No banner

```json
{
  "message": null,
}
```

#### Information

```json
{
  "message": "This is some information",
  "severity": "info"
}
```

#### Warning message

```json
{
  "message": "This is a warning",
  "severity": "warning"
}
```

