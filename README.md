# Mon package DatePICKER

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
Pour l'utiliser, je déclare mes variables pour chaque input que je souhaite utiliser.
Vous pouvez en utiliser autant que vous voulez.

```js
  const [selectedBirthDate, setSelectedBirthDate] = useState(null);

  const handleDateChangeDateBirth = (date) => {
    setSelectedBirthDate(date);
  };
  ```