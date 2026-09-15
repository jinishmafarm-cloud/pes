# PES Sunday Super League

Run `supabase.sql` in the Supabase SQL editor, then add the project URL and anon key to `supabaseConfig` near the top of `script.js`:

```js
const supabaseConfig = { url: 'https://your-project.supabase.co', anonKey: 'your-anon-key' };
```

With Supabase configured, results entered through Admin are shared with every player link. Without it, the app keeps working locally in the current browser.
