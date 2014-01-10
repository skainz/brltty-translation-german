all:
	LC_ALL=C linuxdoc -B txt -l german -c latin BRLTTY.sgml
	sed -e 's/\x1B\[[0-9][0-9]*m//g' -i BRLTTY.txt
	LC_ALL=C linuxdoc -B html -l german -c ascii BRLTTY.sgml
	
clean:
	rm -rf *.html BRLTTY.txt
	

#touch html.made