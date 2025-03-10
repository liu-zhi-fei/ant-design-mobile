# CapsuleTabs

<code src="./demos/index.tsx"></code>

## CapsuleTabs

### Props

| Name             | Description                                                                | Type                    | Default                     |
| ---------------- | -------------------------------------------------------------------------- | ----------------------- | --------------------------- |
| activeKey        | The `key` of the currently active `tab` panel                              | `string \| null`        | -                           |
| defaultActiveKey | The initialized `key` of the selected panel, if the `activeKey` is not set | `string \| null`        | the `key` of the 1st pannel |
| onChange         | Callback when switching panel                                              | `(key: string) => void` | -                           |

## CapsuleTabs.Tab

| Name        | Description                                       | Type        | Default |
| ----------- | ------------------------------------------------- | ----------- | ------- |
| key         | Corresponding to `activeKey`                      | `string`    | -       |
| title       | The displayed text of the tab header              | `ReactNode` | -       |
| disabled    | Whether to disable the tab                        | `boolean`   | `false` |
| forceRender | Whether to render the `DOM` structure when hidden | `boolean`   | `false` |
