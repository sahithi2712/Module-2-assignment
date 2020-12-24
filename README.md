{
    box-sizing: border-box;
    font-family: Helvetica;
}

body {
    background-color: #d6d6d6;
}

h1 {
    text-align: center;
    color: black;
}

section {
    border: 1px solid black;
    background-color: #b5c4d2;
    margin: 10px;
}

section>h2 {
    float: right;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    margin: 0;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    height: 45px;
    padding-top: 10px;
}

section.lebesgue>h2 {
    background-color: #76b8db;
}

section.fubini>h2 {
    background-color: #4f7acd;
}

section.luzin>h2 {
    color: #e2e2e2;
    background-color: #10328a;
}

section>p {
    padding: 40px 15px 15px 15px;
}

.row {
    width: 100%;
}


/* Desktop view options */

@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
    }
    .col-lg-1 {
        width: 8.33%;
    }
    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25%;
    }
    .col-lg-4 {
        width: 33.33%;
    }
    .col-lg-5 {
        width: 41.66%;
    }
    .col-lg-6 {
        width: 50%;
    }
    .col-lg-7 {
        width: 58.33%;
    }
    .col-lg-8 {
        width: 66.66%;
    }
    .col-lg-9 {
        width: 74.99%;
    }
    .col-lg-10 {
        width: 83.33%;
    }
    .col-lg-11 {
        width: 91.66%;
    }
    .col-lg-12 {
        width: 100%;
    }
}

