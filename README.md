# taf-get-seqs-from-ids

- This is a taf-app(taf-tool), you can use taffish(https://www.taffish.com) to use this taf-app.
- This taf-app is written by common lisp(with package hanky-lisp: https://github.com/HermitHan/hanky-lisp) with sbcl:2.5.0(docker.io/fukamachi/sbcl:2.5.0)

Get-Seqs-From-IDs: this app use "common lisp"(need hanky-lisp package) to search ids(from a txt file which have line by line ids) from a fasta file(ids in '> ...' line), and format the ids' fasta seqs(or save to an output file)
