# Outer Ring big wallets overview

## Author
@jfnevado

## Description

Outer ring graph was sleeping and sidelining for a long time, and lateralicing but recently it gained a lot of attention, achieving a great performance. At the same time High is another mertaverse project got similar results, resulting in two graph slices with a big correlation.

I was waiting to do a deep research on outer ring so it was the perfect time to do both investigations.

![price-gq](plots\gq-busd.png)
![price-high](plots\high-busd.png)

## Steps
- Data retrieval through APIs
  - BSC Api
  - CoinGecko
- Data cleaning
- Data transformation
- Data visualization

## Comparative Conclusion

Hipothesis: there are alpha groups doing calls of both tokens, making them perform quite close.

![price-comparative](plots\comparative-price.png)

Results: only 2.12% of the wallets bought both tokens.

| Token | Wallets |
|-------|---------|
| GQ    | 987     |
| HIGH  | 1507    |
| Ambos | 53      |

We can conclude this was pure coincidence, these tokens perform besides being opposite to the whole market performance has nothing in coomon. 

## Analysis Conclusion
### Points
- Balance and transactions(#balance and transactions)
- Day activity
- Group distribution
- Seed investors

### Balance and transactions

With the balance flow, we want to see the relationship between people selling tokens and buying them. And we can observe that at the launch of the token, besides the pump of the token, the inflow was low relative to the token vesting sellers. As a result, it managed to pump due to the low volume of tokens in circulation.

![price-comparative](plots\comparative-price-balance-tx.png)

### Day activity

The activity is quite similar during the whole week but we can see a big positive flow during the sundays.

![price-comparative](plots\tx-by-days-names.png)
![price-comparative](plots\tx-balance-by-days-names.png)

### Group distribution

We can see that the majority of the tokens are in the staking, and the pressure from ventures/investors will end soon

![price-comparative](plots\wallet-type-balance.png)

![price-comparative](plots\wallet-type-send-recibe-tx.png)

### Seed investors

We can observe that only 17.97% of the seed investers sold their tokens, 3.84% of them steaked and 7.91% even bought more.

## Conclusion

Galactiq Quadrant token is quite healthy.

## Run Locally
Initialize git

```bash
git init
```


Clone the project

```bash
git clone https://github.com/**********
```

enter the project directory

```bash
cd **********
```

Create a conda virtual environment and install all the packages from the environment.yml (recommended)

```bash
conda env create --prefix <env_name> --file assets/environment.yml
```

Activate the conda environment

```bash
conda activate <env_name>
```

List all the packages installed

```bash
conda list
```
