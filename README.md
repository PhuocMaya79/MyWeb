/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body */
body {
    font-family: 'Segoe UI', Tahoma, sans-serif;
    background: #f4f6f9;
    color: #333;
    line-height: 1.6;
}

/* Container */
.container {
    width: 90%;
    max-width: 1200px;
    margin: 40px auto;
}

/* Tiêu đề */
h1, h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #2c3e50;
}

/* Grid 3 cột */
.grid-3 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

/* Card */
.card {
    background: #fff;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.card h3 {
    margin-bottom: 10px;
    color: #4a90e2;
}

.card p {
    font-size: 14px;
    color: #555;
}

/* Hover hiệu ứng */
.card:hover {
    transform: translateY(-8px);
    box-shadow: 0 6px 18px rgba(0,0,0,0.15);
}

/* Button */
.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 14px;
    background: #4a90e2;
    color: white;
    border-radius: 6px;
    text-decoration: none;
    font-size: 14px;
}

.btn:hover {
    background: #357abd;
}

/* Responsive */
@media (max-width: 992px) {
    .grid-3 {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 600px) {
    .grid-3 {
        grid-template-columns: 1fr;
    }
}
