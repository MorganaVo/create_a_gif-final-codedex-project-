# create_a_gif-final-codedex-project-
import imageio.v3 as iio  filenames = ["normal.png", "smile.png"] images = []  for file in filenames:     images.append(iio.imread(file))  iio.imwrite("robot.gif", images, duration=500, loop=0) 
