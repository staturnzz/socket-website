cd repo
python3 scan.py -m ./debs > Packages
rm -rf Packages.bz2
bzip2 Packages
