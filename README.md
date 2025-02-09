DALL·E Image Generator 🚀

A Python-based project that uses the OpenAI API to generate images from text prompts using DALL·E. This tool makes it easy to create AI-generated images with just a few lines of code.

---

## Features 🌟
- Generate high-quality images from custom text prompts.
- Simple Python interface using OpenAI's DALL·E API.
- Easily customizable and extendable.

---

## Installation ⚙️

1. **Clone the repository:**
   ```bash
   git clone https://github.com/deepanshuvermaa/dalleimagegenerator.git
   cd dalleimagegenerator

## Set up a virtual environment    
  python -m venv venv
  source venv/bin/activate  # On Linux/Mac
  venv\Scripts\activate     # On Windows

## Install the required dependencies:  
  pip install -r requirements.txt


## Add your OpenAI API key: Create a .env file and add your OpenAI API key:
  OPENAI_API_KEY=your_openai_api_key_here

## Usage 🖼️
 1->Run the script:
     python tryme.py
     
 2->Modify the prompt in tryme.py to generate different images:
     response = openai.Image.create(
     prompt="A futuristic cityscape at sunset",
     n=1,
     size="1024x1024"
)
 3->The generated image will be saved or displayed per your implementation.

## Example Output ✨
Here’s an example image generated using the prompt: "A white Siamese cat sitting on a beach at sunset".
![generated images](https://github.com/user-attachments/assets/ff20fe3b-9f20-43d9-966c-46f6df910aa8)


## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments 🙏
OpenAI for their powerful DALL·E API
Contributors and the open-source community

