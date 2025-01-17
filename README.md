Author: Habiba Saad 
   ID: 443301384
*/
/* Purpose: Stylesheet for the Electronics Store website */

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    box-sizing: border-box;
}

/* Header Styles */
header {
    background: radial-gradient(#fff, #ffb100);
    color: #000000;
    padding: 20px;
    text-align: center;
}

nav {
    margin-bottom: 20px;
    display: flex;
    justify-content: flex-end;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav ul li a {
    color: #000000;
    text-decoration: none;
    padding: 10px 15px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #555;
    color: #fff;
}

/* Footer Styles */
footer {
    background: radial-gradient(#fff, #ffb100);
    color: #000000;
    text-align: center;
    padding: 10px;
}

/* Index Page Styles */
.row {
    display: flex;
    align-items: center;
    flex-wrap: nowrap;
    justify-content: space-around;
}

header .row {
    margin-top: 50px;
}

.col-2 {
    flex-basis: 50%;
    min-width: 300px;
}

.btn {
    display: inline-block;
    color: #000;
    padding: 8px 30px;
    margin: 30px 0;
    background: radial-gradient(#fff, #ffb100);
    border-radius: 30px;
    transition: background 0.5s;
    text-decoration: none;
}

.col-2 img {
    max-width: 100%;
    padding: 50px 0;
}

/* Product Styles */
section {
    margin: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.product {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    width: 42%;
    margin: 20px;
    background-color: #f9f9f9;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.product:hover {
    transform: translateY(-5px);
}

.product img {
    width: 100%;
    max-width: 300px;
    height: auto;
    border-radius: 10px;
    margin-bottom: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.product h3 {
    text-align: center;
    margin-top: 20px;
    font-size: 1.5rem;
    color: #333333;
}

.product ul {
    list-style-type: none;
    padding: 0;
}

.product ul li {
    margin-bottom: 10px;
    color: #666666;
}

.product p {
    text-align: center;
    font-weight: bold;
    margin-top: 20px;
    font-size: 1.2rem;
    color:#ffb100;
}

.title h2 {
    text-align: center;
    position: relative;
    line-height: 60px;
}

.title::after {
    content: '';
    background: #ffb100;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}

/* Product Page Styles */
table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
}

th, td {
    padding: 10px;
    border: 1px solid #ddd;
}

th {
    background-color: #f2f2f2;
}

.product h2 {
    margin-top: 20px;
    font-size: 1.8rem;
    color: #333333;
}

.product h3 {
    font-size: 1.4rem;
    color: #666666;
}

.product ul {
    list-style-type: none;
    padding: 0;
}

.product ul li {
    margin-bottom: 10px;
}

.product p {
    font-size: 1.2rem;
    color: #ffb100;
}

/* Product Enquiry Page Styles */
section {
    margin-bottom: 40px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section h2 {
    color: #333333;
    margin-bottom: 20px;
}

section p {
    color: #666666;
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-wrap: wrap;
}

label {
    font-weight: bold;
    flex: 1 0 100%;
}

input[type="text"],
input[type="email"],
input[type="tel"],
select,
textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 14px;
    flex: 1 0 calc(50% - 20px);
    margin-right: 20px;
}

textarea {
    resize: none;
    height: 100px;
}

button {
    padding: 10px 20px;
    background-color: #ff6600;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #e55e00;
}

/* Table Styles */
table {
    width: 100%;
    border-collapse: collapse;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0px 16px 8px rgba(0, 0, 0, 0.1);
}

thead {
    background-color: #ff6600;
    color: #000000;
}

th, td {
    padding: 15px;
    border-bottom: 1px solid #ccc;
    text-align: left;
}

tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

/* Enhancements Page Styles */
section[style*="background-image"] {
    padding: 20px;
    color: #fff;
    background-size: cover;
}

section[style*="background-image"] h2 {
    margin-top: 0;
}

section[style*="background-image"] table {
    width: 80%;
    margin: auto;
    background-color: rgba(0, 0, 0, 0.5);
}

section[style*="background-image"] th,
section[style*="background-image"] td {
    padding: 10px;
    border: none;
    border-bottom: 1px solid #f9cf00;
    color: #f0a400;
}


/* Student Details Section */
section:nth-of-type(1) {
    margin-bottom: 40px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section:nth-of-type(1) h2 {
    color: #333333;
    margin-bottom: 20px;
}

section:nth-of-type(1) table {
    width: 100%;
    border-collapse: collapse;
}

section:nth-of-type(1) th,
section:nth-of-type(1) td {
    padding: 10px;
    border-bottom: 1px solid #ccc;
    text-align: left;
}

section:nth-of-type(1) th {
    background-color: #f2f2f2;
}

section:nth-of-type(1) a {
    color: #ff6600;
}

/* Assignment Requirements Section */
section:nth-of-type(2) {
    margin-bottom: 40px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section:nth-of-type(2) h2 {
    color: #333333;
    margin-bottom: 20px;
}

section:nth-of-type(2) p {
    color: #666666;
    margin-bottom: 20px;
}

section:nth-of-type(2) ul {
    list-style-type: none;
    padding: 0;
}

section:nth-of-type(2) li {
    margin-bottom: 10px;
}

section:nth-of-type(2) a {
    color: #ff6600;
}

/* Reflection Section */
section:nth-of-type(3) {
    margin-bottom: 40px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section:nth-of-type(3) h2 {
    color: #333333;
    margin-bottom: 20px;
}

section:nth-of-type(3) p {
    color: #666666;
    margin-bottom: 20px;
}
