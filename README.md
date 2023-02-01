# ML Art challenge

This challenge is aimed on creation of AI that capable to determine a genre of an artwork based on its visual appearance. Visual appearance of an artwork is represented by photos that are carefully distributed into categories.

This was a wonderful opportunity to try and implement error correction code approach to classification. Rather than creating a number of separate binary classifiers, the neural network was designed to be trained on class codes rather than plain classes.

An elegant non-iterative self calibrating solution to probability estimates for such a classifier from [Reducing multiclass to binary by coupling probability estimates](https://proceedings.neurips.cc/paper/2001/file/abdbeb4d8dbe30df8430a8394b7218ef-Paper.pdf) by Bianca Zadrozny was used.

This solution scored 5th place at https://codenrock.com/contests/masters-of-art


**Units required:**

- Pandas
- PyTorch
- skorch
- timm
- scikit-learn
- PIL
- NumPy
- Matplotlib
- Seaborn
