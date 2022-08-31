# Start App
```bash
/> npm start
```
## Routes
- აპლიკაციისათვის როუტები გაწერილია App.jsx-ში

## State Managment
- თანამშრომლისა და ლეპტოპის ფილდებისათვის გამოყენებულია გლობალური სთეითი და შეტანილი ინფო ინახება localStorage-ში რათა უკან დაბრუნებისას ცვლილებები შენარჩუნდეს
- გლობალური სთეით მენეჯმენტისათვის გამოყენებულია useContext API
- შესაბამისი ფაილი შექმნილია contexts საქაღალდეში
- მის გამოსაყენებლად შექმნილი AppProvider გაწერილია index.js (root file)-ში

## Styles
- სტილებზე სამუშაოდ გამოყენებულია scss
- მისთვის განკუთვნილი ყველა ფაილი შექმნილია styles საქაღალდეში
- ფეიჯებისთვისა და კომპონენტების scss ფაილებისათვის გამოყოფილია ცალკე ფოლდერები

## Recording add flow
- ჩანაწერის დამატებისას გადავდივართ StaffInfoPage-ზე
- მისი ველების შევსების შემდეგ კი LaptopInfoPage-ზე (სხვა შემთხვევაში ვერ გადავალთ ამ გვერდზე)
- ლეპტოპის ინფოსთვის განკუთვნილი ველების წარმატების შემთხვევაში გადავთივართ SuccessPage-ზე (სხვაგვარად ვერ შევძლებთ ამ გვერდზე გადასვლას)
- SuccessPage-ის დატოვების შემდეგ იშლება localStorage-ში შენახული ინფო

