# Simple-NNUE Chess Evaluator

A simple yet powerful **NNUE** (Efficiently Updatable Neural Network) based **chess evaluation engine**,  
trained on Stockfish evaluations, written in **Python** — optimized for learning, experimentation, and future extensions. ♟️

---

## 🧠 What This Project Does

- Collects chess positions labeled with Stockfish evaluations.
- Extracts king-relative features from chess boards.
- Defines and trains a lightweight NNUE neural network using PyTorch.
- Provides fast board evaluation based on trained weights.
- Designed to be extensible for building full chess engines.

---

## 🔥 Current Features

✅ Random chess position generation.  
✅ Data labeling using Stockfish.  
✅ King-relative feature extraction (9x9 grid).  
✅ Lightweight NNUE model (two hidden layers).  
✅ Training pipeline using PyTorch.  
✅ Incremental feature update after moves (basic).  
✅ Saving and loading trained models.  
✅ GPU/CPU compatible for Colab and local runs.  
✅ Evaluation of live chess positions.

---

## 🚀 Future Scope and Improvements

🔵 **Feature Engineering**
- Add more complex features: mobility, attack maps, pawn structures.

🔵 **Training**
- Train on millions of positions for stronger accuracy.
- Use real self-play games to generate new datasets.

🔵 **Incremental Updates**
- Perfect and optimize incremental feature updates for instant evaluation.

🔵 **Model Enhancements**
- Introduce deeper NNUE architectures.
- Add techniques like residual connections, batch normalization, quantization.

🔵 **Chess Engine Integration**
- Use this NNUE as an evaluation function inside Alpha-Beta or MCTS search engines.
- Build a full-fledged chess engine competing in tournaments.

🔵 **Optimization**
- Compress model to int8/int16 for faster inference.
- Train using TPU/GPUs for faster dataset handling.

🔵 **Self-Learning**
- Implement reinforcement learning like AlphaZero (self-play based training).

🔵 **Deployment**
- Export models for mobile apps, browser-based engines, and lightweight devices.

---

## 📦 Installation

```bash
pip install python-chess stockfish torch
