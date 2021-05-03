# ICSI660-Final-Project

## Step 1.
Run tdbloader:
```bash
tdbloader Ingredients.nq LunchRecipes.nq MainDishes.nq MeatAndPoultry.nq
```

## Step 2.
Run tdbquery to test load:
```bash
tdbquery --loc=DB --query test.rq
```
Output should be a table continaing the count of distinct recipes. Should be 50.
