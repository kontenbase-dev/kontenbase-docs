---
title: $nin
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import CodeBlock from '@theme/CodeBlock';
import NinJs from '!!raw-loader!./snippets/nin-js.md';
import NinApi from '!!raw-loader!./snippets/nin-api.md';

Find all records where the property does not match any of the given values.

<Tabs>
  <TabItem value="javascript" label="Javascript" default>
    <CodeBlock className="language-jsx">
      {NinJs}
    </CodeBlock>
  </TabItem>
  <TabItem value="API" label="API">
    <CodeBlock className="language-jsx" title="[GET]">
      {NinApi}
    </CodeBlock>
  </TabItem>
</Tabs>
