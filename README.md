# sha1-collider
Generate two PDFs with different contents but identical SHA1 hashes.

# Usage
```sh
$ python3 collider.py ./sample/a.jpg ./sample/b.jpg
```
Requirements
- PIL / Pillow
- PyCrypto


# Sample Output
Successfully Generated Collision PDF !!!

#shasum a-collision.pdf
-4bd43d6e15b4b4a423a850afc148fb8df03a4f51  a-collision.pdf

#shasum b-collision.pdf
-4bd43d6e15b4b4a423a850afc148fb8df03a4f51  b-collision.pdf
