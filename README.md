import fal_client

handler = fal_client.submit(
    "fal-ai/aura-flow",
    arguments={
        "prompt": "Close-up portrait of a majestic iguana with vibrant blue-green scales, piercing amber eyes, and orange spiky crest. Intricate textures and details visible on scaly skin. Wrapped in dark hood, giving regal appearance. Dramatic lighting against black background. Hyper-realistic, high-resolution image showcasing the reptile's expressive features and coloration."
    },
)

result = handler.get()
print(result)

Api
export FAL_KEY="your-fal-key"
