# QuizMaster

## Learn to use

UI
- TextMeshPro
- Vertical Layout Group

## something new to me

```csharp
[CreateAssetMenu(menuName = "Quiz Question", fileName = "New question")]
public class QuestionSO : ScriptableObject{
    [TextArea(2,6)]
    [SerializeField]
    string question = "Enter new question text here";
}
```