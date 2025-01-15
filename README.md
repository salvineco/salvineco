## Hi there 👋
# 👋 Hi there! I'm Alec
*Biotech & Genomics Enthusiast | Exploring the World of Biological Data*

Welcome to my GitHub! I’m passionate about all things biotechnology and genomics, and I love experimenting with new tools and technologies to understand the biological world on a deeper level. Whether it’s analyzing complex data, building tools to enhance research, or learning about the latest developments in genomics, I’m always up for a challenge.

## 🔬 About Me
I’m a **biotech and genomics enthusiast** with a keen interest in exploring the frontiers of biological science. My work involves:

- 🌱 **Biotech & Genomics**: Diving deep into genetics, molecular biology, and computational biology.
- 🛠️ **Tools and Tech**: Experimenting with cutting-edge tools, algorithms, and software to process and analyze biological data.
- 

## 🌐 Let’s Connect!
Feel free to reach out to me or check out some of my projects below. I’m always open to collaborations, discussions, and learning from others in the field of biotech and genomics.

- 📬 Email: alec98115@gmail.com

Thanks for visiting my profile! 🚀
## 🎮 Fun Game: Guess the Number!
Take a break and try out this simple game right in your terminal! 

```python
import random

def guess_the_number():
    print("Welcome to 'Guess the Number'!")
    print("I'm thinking of a number between 1 and 100.")
    
    number = random.randint(1, 100)
    guess = None
    attempts = 0
    
    while guess != number:
        guess = int(input("Make a guess: "))
        attempts += 1
        
        if guess < number:
            print("Too low! Try again.")
        elif guess > number:
            print("Too high! Try again.")
        else:
            print(f"Congratulations! You guessed the number in {attempts} attempts.")
            break

if __name__ == "__main__":
    guess_the_number()
