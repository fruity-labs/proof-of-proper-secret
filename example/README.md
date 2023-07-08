# Proof-of-proper-secret

## Check Proper Secret example

This mini-project illustrates how to import and use `check_secret_is_proper(private_secret_input, nb_of_char_types_required)` from `proof_of_proper_secret` public Noir library.

## Run the proof generation & verification

```bash
cd example/
nargo prove proper_stuff
nargo verify proper_stuff
```

## Notes

If you use the function in your project, make sure the secret input `private_secret_input` (typically, a password) is indeed a private input, while `nb_of_char_types_required` would be public.