# \<prism-table\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Prhythm/prism-table)

`<prism-table>` is a [Polymer 2](http://polymer-project.org/) element provides table structure in material design and responsive.

# Usage

```html
<prism-table>
    <prism-thead>
        <prism-tr>
            <prism-th>OrderDate</prism-th>
            <prism-th>Region</prism-th>
            <prism-th>Rep</prism-th>
            <prism-th>Item</prism-th>
            <prism-th>Units</prism-th>
            <prism-th>UnitCost</prism-th>
            <prism-th>Total</prism-th>
        </prism-tr>
    </prism-thead>
    <prism-tbody>
        <prism-tr>
            <prism-td title="OrderDate">1/6/2016</prism-td>
            <prism-td title="Region">East</prism-td>
            <prism-td title="Rep">Jones</prism-td>
            <prism-td title="Item">Pencil</prism-td>
            <prism-td title="Units">95</prism-td>
            <prism-td title="UnitCost">1.99</prism-td>
            <prism-td title="Total">189.05</prism-td>
        </prism-tr>
        <prism-tr>
            <prism-td title="OrderDate">1/23/2016</prism-td>
            <prism-td title="Region">Central</prism-td>
            <prism-td title="Rep">Kivell</prism-td>
            <prism-td title="Item">Binder</prism-td>
            <prism-td title="Units">50</prism-td>
            <prism-td title="UnitCost">19.99</prism-td>
            <prism-td title="Total">999.50</prism-td>
        </prism-tr>
    </prism-tbody>
</prism-table>
```

## Styling

`<prism-table>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--var-prism-table-font-size` | Font size | `inherit`
`--var-prism-table-font-weight` | Font weight | `inherit`
`--var-prism-table-background-color` | Table background | `transparent`
`--var-prism-table-cell-condense` | Cell padding | `0.8em`
`--var-prism-table-row-hover-background-color` | Hovered row background color | `#c5c5c5`
`--var-prism-table-row-hover-color` | Hovered row text color | `inherit`
`--var-prism-table-row-stripe-background-color` | Striped row background color | `#f5f5f5`
`--var-prism-table-row-stripe-color` | Striped row text color | `inherit`
`--var-prism-table-row-selected-background-color` | Striped row background color | `#454545`
`--var-prism-table-row-selected-color` | Striped row text color | `white`

# Licence

MIT Licence