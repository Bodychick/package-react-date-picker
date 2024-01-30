# Mon package DatePICKER

Le package vous permet d'ajouter un input date à votre application.
Vous pourrez :
- ajouter une date de début et une date de fin (pour la sélection)
- ajouter un id
- label
- fonction (pour récupérer la valeur sélectionnée)

## Comment utiliser le package 

```js
<DateRangePicker
    onDateChange={handleDateChangeDateBirth}
    startDate2="2023-10-10"
    endDate2="2023-12-24"
    label="Date de naissance"
    id='date-of-birth'
/>
```

## Exemple d'utilisation
Pour l'utiliser, je déclare mes variables dans mon fichier principal pour chaque input que je souhaite utiliser.
Vous pouvez en utiliser autant que vous voulez.


```js
  const [selectedBirthDate, setSelectedBirthDate] = useState(null);

  const handleDateChangeDateBirth = (date) => {
    setSelectedBirthDate(date);
  };
  ```

  # Versions 
  Testé  sur ces différentes versions
  - NodeJS : "^20.7.0"
  - react: "^18.2.0"
  - react-dom: "^18.2.0"
  - react-redux: "^8.1.3"
  - react-scripts: "^3.0.1"
  - styled-components: "^6.1.3"
