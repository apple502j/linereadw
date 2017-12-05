LinereadW is a library.
Like that:
  linereadw("This is a library.\nIt is licensed under both MIT, 2-clause BSD, and CC BY 1.0-4.0.\nThank you for reading.",1)
becomes:
  This is a library. [ENTER]
  It is licensed under both MIT, 2-clause BSD, and CC BY 1.0-4.0. [ENTER]
  Thank you for reading. [ENTER]
("[ENTER]" won't be shown)

  linereadw(string,per line)
