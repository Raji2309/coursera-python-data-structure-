# coursera-python-data-structure-
assignment 7.1
# Use words.txt as the file name
fname = input("Enter file name: ")
fh = open(fname)
for lx in fh:
    ly = lx.upper()
    lz = ly.strip()
    print(lz)
