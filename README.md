# KvUmbrella

A simple Key-Value Store written in Elixir.

Built based on the totorial at https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html

## Usage

You will need to have [Elixir](https://elixir-lang.org) installed in order to get started.

```
mix run --no-halt

# in a separate terminal:

telnet 127.0.0.1 4040
```

In your telnet session you can run things like:

```
CREATE shopping
OK

PUT shopping milk 1
OK

PUT shopping eggs 3
OK

GET shopping milk
1
OK

DELETE shopping eggs
OK
```

