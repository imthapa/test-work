this is demo for checking author name when there are multipe name in .gitconfig
2nd user name was picked in previus commit.lets see whats this time, i have swapped the two users in .gitconfig
so its final that git always picks the last user.name from .gitconfig file,thus its of no use of having multiple user.name in .gitconfig file
and if you want have multiple user.name, then keep one in global and other particular to repository by using commands

for global setup
git config --global user.name "<your name>"
git config --global user.email "<your email>"

for repository
git config user.name "<your 2nd_name>"
git config user.email "<your 2nd_email>"

the repository user.name overrides the global when commit is made in that particular repository



this is from demo branch!!!!!!!!!!!!!!!!!!!!!!!!
