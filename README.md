# bitmonk_kafka-cookbook

[![Join the chat at https://gitter.im/bitmonk/bitmonk_kafka](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/bitmonk/bitmonk_kafka?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['bitmonk_kafka']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### bitmonk_kafka::default

Include `bitmonk_kafka` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[bitmonk_kafka::default]"
  ]
}
```

## License and Authors

Author:: YOUR_NAME (<YOUR_EMAIL>)
