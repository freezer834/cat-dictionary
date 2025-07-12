# 🐱 Cat Dictionary API

Welcome to the **Cat Dictionary API** – a fun and simple API that provides definitions for common cat-related terms, sounds, and behaviors!

## 📂 File

- `dictionary.json`: Contains the full list of cat vocabulary with explanations.

## 📑 Format

The JSON structure is as follows:

```json
{
  "status": "success",
  "message": "Welcome to the Cat Dictionary API",
  "data": {
    "word": "definition",
    ...
  }
}
```

Example entry:

```json
"meow": "A common cat vocalization. Can mean attention, greeting, or demand."
```

## 📚 Included Words

- `meow`: A vocal sound for attention or greeting.
- `purr`: A soft sound of contentment.
- `hiss`: A warning when scared or angry.
- `mrrp`: A trill-like greeting sound.
- `yowl`: Loud, emotional cry (mating or distress).
- `chirp`: High-pitched sound, often when observing prey.
- `blep`: Tongue sticking out slightly.
- `zoomies`: Sudden hyperactive behavior.
- `boop`: Gently touching a cat's nose or face.
- `loaf`: Cat tucking its paws under its body.
- `biscuit`: Kneading motion with paws.
- `tail-flick`: Sign of irritation or focus.
- `slow-blink`: A sign of affection or trust.

## 📦 Usage

This can be used in:

- Cat-themed websites
- Educational apps
- Fun games or pet projects
- APIs returning cat terms

## ⚠️ Note

This is a static API. For dynamic features (search, types, add/remove), you may need to create a backend or integrate it with a web server.
