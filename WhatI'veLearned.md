January 21, 2026

SMILES stands for Simplified Molecular Input Line Entry System. International Chemcial Identifier (InChl) seems to be the official standard as determined by IUPAC, but SMILES has some infrastructure built up around it.
Brackets are used to specify the charge of atoms eg. [NH4+] is ammonium. If the atoms have no charge, are from the set of "organic" elements, (Boron, Carbon, Nitrogen, Oxygen, Phosphorous, Sulfur, Fluroine, Clroine, Bromine, or Iodine), have the standard amount of attached hydrogens, have the normal amount of neutrons, and are not "chiral centers" then they do not need brackets around them.

A label in ML context refers to the "correct" answer.

For large datasets, we want to call .itersamples on the dataset and iterate through it. That way, when you do not have enough memory to load all of the dataset, you can still view the dataset by loading segments of it iteratively. An alternative is using iterbatches, where you can specify batch_size. The boolean parameter deterministic will determine whether you get the same result each time.
This actually answers my question of, what happens if your dataset is too big? ie., how do companies like Facebook and Google process/see their data, because I doubt they have a computer with enough memory to hold all of the data.

You can also just copy things to a pandas dataFrame with to_DataFrame()

Using np.random.random_sample or np.random.Generator.random is the more up to date version of using np.random.

