Use this same strategy to remove the single quote marks (<code>'</code>), the right square brackets (<code>]</code>), and spaces from the <code>items_owned</code> column.

<details>
  <summary>
    Solution
  </summary>
  

1. <code>value.replace("'", "")</code>
1. <code>value.replace("]", "")</code>
1. <code>value.replace(" ", "")</code> You should now have a list of items separated by semi-colons (<code>;</code>).

</details>

[Episode 2 Exercise 3](episode2_ex3.md)
