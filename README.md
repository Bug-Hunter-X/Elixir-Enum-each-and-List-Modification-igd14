# Elixir Enum.each and List Modification Bug

This repository demonstrates a common pitfall in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The example shows how `List.delete` within the loop does not affect the original list.

The solution demonstrates how to use `Enum.filter` for the intended behavior.