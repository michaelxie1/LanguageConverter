# LanguageConverter
This will translate captions
#Translator
from translate import Translator
translator= Translator(from_lang="japanese",to_lang="english")
translation = translator.translate("おはようございます")
print(translation)
