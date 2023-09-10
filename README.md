
Python script to generate universis access tokens without oauth2

Αυθεντικοποιητής για το universis του Αριστοτελείου Πανεπιστημίου Θεσσαλονίκης, ΑΠΘ

*Είναι πολύ ενοχλητικό το ΑΠΘ στα αγγλικά να λέγεται AUTh που επίσης σημαίνει αυθεντικοποιητής*

## Example:

```bash
$ pip install AUTh-authenticator
```

```python
from AUTh_authenticator import universis

universis.generate_token("username", "password")
# "eyJhjGciOvJSUzI1NiIzInR5cCI..."

```
