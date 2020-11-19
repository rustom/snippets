Convert .mov or .mp4 files to gifs on MacOS (requires ffmpeg, imagemagick, gifsicle installation)
'''
ffmpeg -y -i input.mp4 -f image2pipe -vcodec ppm - | convert -delay 2 -loop 0 -layers Optimize - gif:- | gifsicle -d 3 -O3 -o optimized.gif
'''
