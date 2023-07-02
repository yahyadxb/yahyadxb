# قائمة بالردود العشوائية
‏responses = [
    "أهلاً بك!",
    "كيف يمكنني مساعدتك؟",
    "أنا آلة تعلم ذكاء اصطناعي.",
    "أسألني أي شيء!",
    "لا أعرف الإجابة على هذا السؤال."
]

‏def get_response(user_input):
    # توليد رد عشوائي
‏    return random.choice(responses)

# تجربة البرنامج
‏while True:
‏    input_text = input("أكتب شيئاً:")
‏    response = get_response(input_text)
‏    print(response)
```
