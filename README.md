# BMI & Calorie Calculator

A small, dependency-free JavaScript web tool that calculates BMI and estimates daily calorie needs. Everything runs in your browser; no data is sent anywhere.

> For adults 18+. This tool gives estimates only and is not medical advice.

## Features

- **BMI:** value, category (underweight, healthy, overweight, obesity), and a visual scale.
- **Healthy weight range** for your height.
- **Calories:** resting rate (BMR) and daily needs by activity level, using the Mifflin-St Jeor equation.
- **Targets:** slow/steady loss and gain options, with a safety floor so loss targets never drop below 1,200 kcal (women) or 1,500 kcal (men).
- **Metric and imperial** units, live results as you type, mobile friendly, dark mode.

## Usage

No install or build step:

1. Download `index.html` and open it in any browser, or
2. Host it free with **GitHub Pages**: *Settings → Pages → Deploy from branch → `main` / root*.

## Formulas

- BMI = weight (kg) / height (m)²
- BMR (men) = 10 × kg + 6.25 × cm − 5 × age + 5
- BMR (women) = 10 × kg + 6.25 × cm − 5 × age − 161
- Daily calories = BMR × activity factor (1.2 to 1.9)

## Limitations

BMI doesn’t distinguish muscle from fat and isn’t suited to children, pregnant women, or some athletes. For personal guidance, see a doctor or registered dietitian.

## Project structure

```
bmi-calorie-calculator/
├── index.html   # the whole app (HTML + CSS + JavaScript)
├── README.md
└── LICENSE
```

## License

MIT, see [LICENSE](LICENSE).
