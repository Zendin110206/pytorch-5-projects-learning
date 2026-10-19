# PyTorch, Slowly This Time

Learning PyTorch from scratch by following along with **Omar M. Atef's** five-project course, on my own laptop, typing every line myself.

---

## Why this repo exists

Honestly? I got burned out.

For a while now, I've been using Codex and Claude Code for basically everything. I'd write a prompt and let them do the work. Even creating a repo or writing its description, I handed that off too. And the longer it went on, the more demotivated I got. It started to feel pointless, like I wasn't learning anything and the only skill I was actually building was prompting.

I mean, sure, it made me way more productive and it solved my problems. But I didn't feel like I was learning at all. If someone asked me what happened in my own project, or why I used this instead of that, my honest answer would probably be: _"Idk, only God and the agent know what the hell actually happened."_ That's not a good place to be. What's the point of building something if I don't understand it? I missed that joy of finally getting how something works.

So this repo is me trying to get it back. Going back to the basics, typing things myself, getting confused, breaking stuff, figuring out why it broke, and actually learning again.

## How I'm doing it

A few rules I'm keeping for myself:

- **Watch, pause, type.** I write every line myself. No copy-pasting from the original notebooks.
- **Understand before moving on.** If I can't explain a cell in my own words, I don't go to the next one.
- **Break things on purpose.** Change a number, delete a line, and see what happens.
- **Run everything locally.** No Colab. Setting things up on my own machine is part of the learning.
- **Slow is fine.** There's no deadline here.

## The course

|                    |                                                                                                           |
| ------------------ | --------------------------------------------------------------------------------------------------------- |
| Instructor         | Omar M. Atef ([YouTube](https://www.youtube.com/@OmarMAtef) · [GitHub](https://github.com/omaratef3221))  |
| Full course        | [Learn PyTorch in 5 Projects – Tutorial](https://www.youtube.com/watch?v=E0bwEAWmVEM) on freeCodeCamp.org |
| Original notebooks | [omaratef3221/pytorch_tutorials](https://github.com/omaratef3221/pytorch_tutorials)                       |

## Progress

| #   | Project                | What it's about                            | Status      |
| --- | ---------------------- | ------------------------------------------ | ----------- |
| 01  | Tabular classification | Rice type, from a CSV file                 | Done        |
| 02  | Image classification   | Animal faces with a CNN built from scratch | Done        |
| 03  | Pretrained image model | Bean leaf lesions with transfer learning   | Done        |
| 04  | Audio classification   | Quran reciters from audio clips            | Done        |
| 05  | Text classification    | Sarcasm detection in headlines with BERT   | Up next     |

## My setup

- Windows 11, NVIDIA RTX 4050 Laptop GPU (6 GB)
- Python 3.12, managed with [uv](https://docs.astral.sh/uv/)
- VS Code with Jupyter notebooks

## Running it yourself

```bash
git clone https://github.com/Zendin110206/pytorch-5-projects-learning.git
cd pytorch-5-projects-learning
uv sync
```

The datasets come from Kaggle and are not stored in this repo. I'll add download steps as I start each project.

## Credits

All the teaching here belongs to **Omar M. Atef**, and big thanks to **freeCodeCamp.org** for putting the full course out for free. The code in this repo is my own retyped and commented version, written while following along. If you want to learn this too, go watch the original. It's really good.
