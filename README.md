# nft
class NFT:
    def __init__(self, name, owner, description, image_url):
        self.name = name
        self.owner = owner
        self.description = description
        self.image_url = image_url

    def display_info(self):
        print("NFT Information:")
        print(f"Name: {self.name}")
        print(f"Owner: {self.owner}")
        print(f"Description: {self.description}")
        print(f"Image URL: {self.image_url}")

# Example usage
