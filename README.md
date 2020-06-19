# 自分で自分にWebPush通知を発行する。

## Usage

```sh
npx serve
```

Access to http://localhost:5000

## Code

```js
await Notification.requestPermission().catch(console.error)
const notif = new Notification('test')
```