---
title: create()
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import CodeBlock from '@theme/CodeBlock';
import CreateJs from '!!raw-loader!./snippets/create-js.md';
import CreateApi from '!!raw-loader!./snippets/create-api.md';

Create a record.

<Tabs>
  <TabItem value="javascript" label="Javascript" default>
    <CodeBlock className="language-jsx">
      {CreateJs}
    </CodeBlock>
  </TabItem>
  <TabItem value="API" label="API">
    <CodeBlock className="language-jsx" title="[POST]">
      {CreateApi}
    </CodeBlock>
  </TabItem>
</Tabs>
