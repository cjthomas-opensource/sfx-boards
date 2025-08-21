default: clean rebuild

clean:
	rm -f processed/*

rebuild: rebuild_rev2


# Photos for the rc2 board.
rebuild_rev2:
	convert -strip -gamma 1.25 \
		-crop 5000x3600+60+100 -resize 1250x900 \
		selected-rev2/selected-accessories.jpg \
		processed/rev2-accessories.jpg
	convert -strip -gamma 1.25 -rotate 0.8 \
		-crop 1250x650+1940+1620 -resize 750x390 \
		selected-rev2/selected-board.jpg \
		processed/rev2-board.jpg



# This is the end of the file.
