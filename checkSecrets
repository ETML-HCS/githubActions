import os

SECRET_ATTENDU = "blabla" 

def verifier_secret():
    secret = os.getenv("MON_SECRET")
    if secret is None:
        print("❌ Secret non défini !")
    elif secret == SECRET_ATTENDU:
        print("✅ Secret valide !")
    else:
        print("❌ Secret invalide !")

if __name__ == "__main__":
    verifier_secret()
