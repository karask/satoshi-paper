# satoshi-paper
Original Satoshi paper in various formats

The epub was created with:
$ pandoc bitcoin.md --webtex --metadata=title:"Bitcoin: A Peer-to-Peer Electronic Cash System"  -s -t html | pandoc -f html -o bitcoin.epub

The mobi was created using calibre with:
$ ebook-convert bitcoin.epub bitcoin.mobi
