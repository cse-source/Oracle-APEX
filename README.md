# APEX Food Menu System

Dynamic food menu card UI built with:

- Oracle APEX
- PL/SQL Dynamic Region
- Custom CSS UI
- Discount & VAT pricing logic

## Features

✔ Dynamic menu cards  
✔ Discount price calculation  
✔ Category based image selection  
✔ Responsive card UI  
✔ Easy integration with POS system  

## Technologies

Oracle APEX  
PL/SQL  
SQL  
HTML  
CSS  

## Installation

1. Import SQL files from `/database`
2. Upload images to APEX Static Files
3. Import APEX page from `/apex/pages`
4. Add CSS from `/frontend/css`

## 📁 Dynamic Region File

## 📁 CSS File
```
frontend/css/combo-card.css

.combo-container{
display:flex;
flex-wrap:wrap;
gap:5px;
}

.combo-card{
width:150px;
border:1px solid #701c1c;
border-radius:8px;
background:#ddd;
box-shadow:0 3px 8px rgba(0,0,0,0.15);
overflow:hidden;
}

.combo-img img{
width:100%;
height:160px;
object-fit:cover;
}

.price-tag{
position:absolute;
top:5px;
right:5px;
background:#1e40af;
color:white;
padding:3px 5px;
font-size:13px;
border-radius:6px;
}

.price-tag .old{
text-decoration:line-through;
text-decoration-color:red;
text-decoration-thickness:2px;
}

.combo-body{
padding:10px;
text-align:center;
}
```

## 📁 Deployment Outlook
<img width="858" height="258" alt="image" src="https://github.com/user-attachments/assets/47243e7c-e0b1-4767-98fd-c0ec91a8f962" />
