from PIL import Image
from os import listdir

dir = "/home/lizzy/images/"
pdf = "/home/lizzy/generated.pdf"

images = [ Image.open(dir + f) for f in sorted(listdir(dir)) ]

images[0].save(pdf, "PDF", resolution=100.0, save_all=True, append_images=images[1:])
