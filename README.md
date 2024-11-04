## Getting Started

- npm i @capacitor/core
- npm i -D @capacitor/cli

- npx cap init

```bash
import type { CapacitorConfig } from '@capacitor/cli';

const config: CapacitorConfig = {
  appId: 'com.vercel.senbox',
  appName: 'senbox',
  webDir: 'out',
};

export default config;
```

- output: 'export', in next.config.mjs

- npm i @capacitor/android @capacitor/ios
- npx cap add android
- npx cap add ios
- npx cap sync
- npx cap open android / ios
- src: https://www.youtube.com/watch?v=S55BrlnLup8&ab_channel=RahulBharati
