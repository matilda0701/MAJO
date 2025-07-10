# MAJO
Building AI course
# Project Title
Painting with AI
## Summary
I woudl like with generative AI Paint a butterfly
#Task
prompt = "A beautiful, colorful butterfly painting, digital art, highly detailed"

# Generate image
image = pipe(prompt, guidance_scale=7.5).images[0]

# Save image
image.save("butterfly_image.png")
print("Butterfly image saved as butterfly_image.png")
