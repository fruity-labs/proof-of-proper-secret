# Noir library by Wagmi Labs*

A public Noir library repo containing a specific useful Noir functions we've implemented and we're using in our apps: __Proof of Proper Secret__.

## Using the library

1. Add the library to your Noir project dependencies in the `Nargo.toml` file.

```toml
[dependencies]
proof_of_proper_secret = {tag = "v1.0.0", git = "https://github.com/fruity-labs/proof-of-proper-secret"}
```

2. Import the library and function into your Noir code.

Example:
```rust
use dep::std;
use dep::proof_of_proper_secret;

fn main(){
    // ...
    proof_of_proper_secret::check_secret_is_proper(hashed_chars, nb_char_types);
    std::println("Proper!");
    // ...
}
```
## Thanks

Credit to [@critesjosh](https://github.com/critesjosh) for [the public Noir library demo](https://github.com/critesjosh/noir-lib-demo).
And cheers to [@signorecello](https://github.com/signorecello) for his guidance and review.

--

**(Wagmi Labs == [@madztheo](https://github.com/madztheo) & [@guelowrd](https://github.com/guelowrd), creators of [Fruity Friends](https://github.com/madztheo/zk-fruits-front-end))*