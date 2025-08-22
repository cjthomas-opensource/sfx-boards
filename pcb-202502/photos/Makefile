default: clean rebuild

clean:
	rm -f processed/*

rebuild: rebuild_v202502a


# Photos for the v202502a board.
rebuild_v202502a:
	convert -strip -gamma 1.25 \
		-crop 3000x1800+1200+900 -resize 1500x900 \
		selected/selected-board.jpg \
		processed/v202502a-board.jpg
	convert -strip -gamma 1.25 \
		-crop 4950x3000+150+150 -resize 1650x1000 \
		selected/selected-speaker.jpg \
		processed/v202502a-speaker.jpg


# This is the end of the file.
