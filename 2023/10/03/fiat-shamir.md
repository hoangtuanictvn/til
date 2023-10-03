# Fiat-Shamir
## Examples:
- `g` is a number everyone knows
- Alice wants to prove that she knows x, such that `y = g^x`
  - She picks a random `v`, -(`t`)-> Bob such that `t = g^v`
  - Bob pics a random `c`, -(`c`)-> Alice
  - Alice sends back `r = v - cx`
  - Bob checks `t = g^r*y^c = g^(v-cx)*g^xc = g^v = t`
  - Bob knows that Alice knows the `preimage` `x`
