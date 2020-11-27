Convert .mov or .mp4 files to gifs on MacOS (requires ffmpeg, imagemagick, gifsicle installation)
'''
ffmpeg -i in.mov -pix_fmt rgb8 -r 10 output.gif && gifsicle -O3 output.gif -o output.gif
'''
