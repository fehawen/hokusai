## hokusai

### About

16-color palettes based on prints by the Japenese ukiyo-e painter and printmaker Katsushika Hokusai.

These palettes are intended to be used with [cpr](https://github.com/fehawen/cpr) for changing palettes randomly.

The palettes are named in ascending order of creation, given an English-ified version of the Japenese name for its order's number starting with *one*, or *ichi*.

### Usage

Clone the repo.

```sh
cd && git clone https://github.com/fehawen/hokusai.git
```

Follow the [installation](https://github.com/fehawen/cpr#install) instructions for `cpr`, but set the environment varialbe `CPR_LIB` to point to this directory instead. That way, `cpr` will use these Hokusai palettes, rather than its default palettes.

```sh
export CPR_LIB=~/hokusai # or wherever you cloned it to
```
