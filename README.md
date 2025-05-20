# EmpathyNet-Emotion-Aware-Conversational-RPG




**📄 README.md**
```markdown
# EmpathyNet: Emotion-Aware Conversational RPG

A story-driven RPG that teaches empathy, gratitude, and social cues through emotionally adaptive conversations.

## Features
- NLP-powered emotion detection
- Dynamic branching dialogues based on emotional state
- Positive reinforcement and emotional reflection for users

## Tech Stack
Unity, C#, Python (for backend NLP), TensorFlow Lite (on-device emotion inference)

## Sample Code Snippets

```csharp
// EmotionTracker.cs
public class EmotionTracker : MonoBehaviour {
    public string currentEmotion;

    public void DetectEmotion(string inputText) {
        currentEmotion = EmotionAPI.Analyze(inputText);
    }
}
