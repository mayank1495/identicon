# Identicon

## Run

Move to the identicon directory. Run elixir with:

    $ iex -S mix
Then run the main function:

    iex> Identicon.main(<name>)
Give your name(any string) in place of `name`. A `name.png` file will be created in the same directory.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

