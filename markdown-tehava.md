# Markdown-tehtävä – Koneoppimiskurssi

## Johdanto

Tässä dokumentissa esittelen **Markdown-kielen** tärkeimmät elementit.
Markdown on *kevyt merkintäkieli*, jota käytetään mm. Jupyter Notebookeissa.

> "Markdown on yksinkertainen tapa muotoilla tekstiä ilman monimutkaisia työkaluja."

---

## Asennetut työkalut

### VS Code -laajennukset

| Laajennus | Tekijä | Käyttötarkoitus |
|-----------|--------|-----------------|
| Markdown All in One | Yu Zhang | Markdown-editori |
| Markdown Preview Mermaid Support | Matt Bierner | Kaavioiden piirto |
| Markdown Emoji | Matt Bierner | Emoji-tuki |

### Python-ympäristö

Kurssilla käytettävät kirjastot:

1. **NumPy** – Matemaattiset operaatiot
2. **Pandas** – Datan käsittely
3. **Matplotlib** – Visualisointi
4. **Scikit-learn** – Koneoppimisalgoritmit

---

## Koodiesimerkkejä

### Matplotlib-importit

    import matplotlib as mpl
    import matplotlib.pyplot as plt
    import numpy as np

### Yksinkertainen kuvaaja

    x = np.linspace(0, 10, 100)
    plt.plot(x, np.sin(x))
    plt.show()

---

## Kuva esimerkki

![Matplotlib logo](https://matplotlib.org/stable/_images/sphx_glr_logos2_003.png)

---

## Markdown-syntaksin yhteenveto

**Lihavoitu teksti** kirjoitetaan `**tekstin ympärille**`

*Kursivoitu teksti* kirjoitetaan `*tekstin ympärille*`

### Järjestetty lista

1. Ensimmäinen kohta
2. Toinen kohta
3. Kolmas kohta

### Järjestämätön lista

- Bullet-kohta
- Toinen kohta
  - Sisennys toimii näin

---

## Hyödyllisiä linkkejä

- [Markdown perussyntaksi](https://www.markdownguide.org/basic-syntax/)
- [Matplotlib dokumentaatio](https://matplotlib.org/)
- [NumPy dokumentaatio](https://numpy.org/doc/)

---

## Yhteenveto

Markdown on helppo oppia. Toimii suoraan Jupyter Notebookeissa. Mahdollistaa selkeän dokumentoinnin.

---

# Lähdekoodi (Source Code)

    # Markdown-tehtävä – Koneoppimiskurssi

    ## Johdanto

    Tässä dokumentissa esittelen **Markdown-kielen** tärkeimmät elementit.
    Markdown on *kevyt merkintäkieli*, jota käytetään mm. Jupyter Notebookeissa.

    > "Markdown on yksinkertainen tapa muotoilla tekstiä ilman monimutkaisia työkaluja."

    ---

    ## Asennetut työkalut

    ### VS Code -laajennukset

    | Laajennus | Tekijä | Käyttötarkoitus |
    |-----------|--------|-----------------|
    | Markdown All in One | Yu Zhang | Markdown-editori |
    | Markdown Preview Mermaid Support | Matt Bierner | Kaavioiden piirto |
    | Markdown Emoji | Matt Bierner | Emoji-tuki |

    ### Python-ympäristö

    Kurssilla käytettävät kirjastot:

    1. **NumPy** – Matemaattiset operaatiot
    2. **Pandas** – Datan käsittely
    3. **Matplotlib** – Visualisointi
    4. **Scikit-learn** – Koneoppimisalgoritmit

    ---

    ## Koodiesimerkkejä

    ### Matplotlib-importit

        import matplotlib as mpl
        import matplotlib.pyplot as plt
        import numpy as np

    ### Yksinkertainen kuvaaja

        x = np.linspace(0, 10, 100)
        plt.plot(x, np.sin(x))
        plt.show()

    ---

    ## Kuva esimerkki

    ![Matplotlib logo](https://matplotlib.org/stable/_images/sphx_glr_logos2_003.png)

    ---

    ## Markdown-syntaksin yhteenveto

    **Lihavoitu teksti** kirjoitetaan **tekstin ympärille**
    *Kursivoitu teksti* kirjoitetaan *tekstin ympärille*

    ### Järjestetty lista

    1. Ensimmäinen kohta
    2. Toinen kohta
    3. Kolmas kohta

    ### Järjestämätön lista

    - Bullet-kohta
    - Toinen kohta
      - Sisennys toimii näin

    ---

    ## Hyödyllisiä linkkejä

    - [Markdown perussyntaksi](https://www.markdownguide.org/basic-syntax/)
    - [Matplotlib dokumentaatio](https://matplotlib.org/)
    - [NumPy dokumentaatio](https://numpy.org/doc/)

    ---

    ## Yhteenveto

    Markdown on helppo oppia.
    Toimii suoraan Jupyter Notebookeissa.
    Mahdollistaa selkeän dokumentoinnin.