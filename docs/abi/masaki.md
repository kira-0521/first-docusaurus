---
sidebar_label: "Y's"
sidebar_position: 6
id: my-doc-id
title: My document title
description: My document description
slug: /my-custom-url
---

# Masaki

This is my **first Docusaurus document**!

[私はまさき](#kamioka)

## Kamioka

- I am masaki


![Docusaurus logo](/img/docusaurus.png)

```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
    return (
        <h1>Hello, Docusaurus!</h1>
    )
}
```

:::tip My tip

Use this awesome feature option

:::

:::danger Take care

This action is dangerous

:::

export const Highlight = ({children, color}) => {
  return (
    <span
      style={{
        backgroundColor: color,
        borderRadius: '20px',
        color: '#fff',
        padding: '10px',
        cursor: 'pointer',
      }}
      onClick={() => {
        alert(link)
      }}>
      {children}
    </span>
    )
};

This is <Highlight color="#25c2a0">I am MDX</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !