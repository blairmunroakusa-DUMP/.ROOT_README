
#### [ROOT](https://github.com/blairmunroakusa)
#### [TRUNK](https://github.com/blairmunroakusaTRUNK)
#### [BRANCH](https://github.com/blairmunroakusaBRANCH)
#### [LEAF](https://github.com/blairmunroakusaLEAF)


```
The nested repo tree:

	       _ ROOT _			< YOU ARE
	      /        \		  HERE
	 TRUNK          TRUNK	
         /    \        /     \
    BRANCH  BRANCH  BRANCH  BRANCH
   / \      / \        / \      / \
LEAF LEAF LEAF LEAF LEAF LEAF LEAF LEAF	
					 
```
```
WELCOME TO MY GIT WORLD PIECE COMPUTER PROTOTYPE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

So far most of the computer and process lives is in my head,
and embedded throughout the ambient stuff in my environment,
but the file system is migrating here to github / my computer,
and to the wp.computer / up.computer domain space.

Because github repos are stored in a flat topology,
I am using organizations to organize my repositories
into three repo 'levels'.

(largely to keep little stuff separated from big stuff,
cloneable stuff separated from mess)

I like trees, but I think trees should only ever have four layers:

	leaves
	branches
	trunks
	root

(Vines can connect between things no problem.)
```
```
In this space (in the context of github) the tree is organized like this:




		  	 ___> leaves	== repos in blairmunroakusaLEAF
		    ____/		   that only contain files / directories
blairmunroakusaLEAF ____	
		  	\___> branches	== repos in blairmunroakusaLEAF
		      __/		   that contain only leaves
blairmunroakusaBRANCH __	
			\___> trunks	== repos in blairmunroakusaBRANCH
		     ___/		   that contain branches, maybe leaves
blairmunroakusaTRUNK ___	  
			\___> bundles	== repos in blairmunroakusa
		________/		   that contain only trunks
blairmunroakusa ________
			\___< root	== my alias



And in this represenation, each repository is a dot, and each submodule or directory is a slash:

root
.bundleN/trunk(M_i)		blairmunroakusa		N bundles,	N_i trunks / bundle
.trunkP/branch(P_j)		blairmunroakusaTRUNK	M trunks,	M_j branches / trunk
.branchP/leaf(Q_k)		blairmunroakusaBRANCH	Q branches,	Q_k leaves / branch
.LeafQ/file.directory(R).ext	blairmunroakusaLEAF	P leaves,	P_l files|directories / leaf

So something like N = N1 + N2 + ... Ni, ..., P = P1 + P2 + ... + Pl

and can be identified like root.bundle.trunk.branch.leaf.file.ext elsewhere.

I am trying to create a namespace that seamlessly extends into my non-electronic life.

I use clustergit and bash scripts to manage this stuff.

Probably nothing new, but this is how I am organizing things with my GH organizations.
...thought you may deserve an explanation, lest the organization drive you mad.

```


