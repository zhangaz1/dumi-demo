---
nav:
  title: foo
  order: 2
---

## Foo

Demo:

```tsx
/**
 * title: 标题内容
 * transform: true
 */

// 组件内容

```

```tsx
import React from 'react';
import { Foo } from 'dumi-lib';

export default () => <Foo style="position: fixed;" title="First Demo" />;
```

<code src="./foo-demo.tsx" title="title: xxx" transform="true"/>


```tsx | inline
import React from 'react';
import { Foo } from 'dumi-lib';

export default () => <Foo title="First Demo" />;
```

<code src="./foo-demo.tsx" inline/>

More skills for writing demo: https://d.umijs.org/guide/demo-principle
