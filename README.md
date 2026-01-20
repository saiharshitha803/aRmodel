>>Phase 1: The Baseline ($74\%$)
Focus: Proving the concept.
The setup: You likely used a simple model or a pre-trained model without much adjustment.
The Fault: High "Paranoia." The model was guessing "AI" for almost everything because it hadn't learned the subtle differences yet.
What you learned: You realized that simple pixel-matching isn't enough to catch modern AI.

Shutterstock
>>Phase 2: Refinement & Augmentation ($85\%$)
Focus: Generalization.
The breakthrough: You added Data Augmentation (flips, zooms, rotations).
The result: By "showing" the model the same image from different angles, you forced it to stop memorizing specific photos and start looking for general patterns.
The Fault: The model became much better, but it still struggled with "High-Quality Realism"—confusing professional photos for AI.


>>Phase 3: Fine-Tuning & Architecture ($88\%$)
Focus: Pixel-level precision.
The breakthrough: You unfroze the top layers of the MobileNetV2 (Stage 2 training) and added Batch Normalization.
The result: This allowed the model to "tune" its filters specifically for AI artifacts. This is where your AI Recall hit 98%, making it an elite detector.
The current state: You have a robust, safe model that almost never misses a fake.

reached Phase 3 successfully.........
