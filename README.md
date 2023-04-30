# myprojectsite
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>My Project</title>
  <base href="/">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <style>
    :host {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    app-menu-bar {
      width: 100%;
    }

    @media only screen and (min-width: 768px) {
      app-menu-bar {
        width: 768px;
      }
    }

    .container__menu-bar {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center;
      width: 100%;
      background-color: #f1f1f1;
      padding: 10px;
      margin-bottom: 20px;
    }

    .container__menu-bar > ul{
      display: flex;
      flex-direction: row;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .container__menu-bar > ul > li{
      margin-right: 20px;
    }

    .container__menu-bar > ul > li:last-child{
      margin-right: 0;
    }

    .container__menu-bar > ul > li > a{
      color: black;
      text-decoration: none;
    }

    .container__menu-bar > ul > li > a:hover{
      text-decoration: underline;
    }

    .container__menu-bar > ul > li > span{
      margin-right: 5px;
    }

    .container__menu-title {
      display: flex;
      justify-content: center;
      margin-bottom: 20px;
    }

    .container__menu-title > h1 {
      font-size: 30px;
    }

    .container__big-card {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100%;
      padding: 20px;
      margin-bottom: 20px;
      background-color: #f1f1f1;
      border: 1px solid #ddd;
    }

    .container__big-card > h2 {
      font-size: 25px;
      margin-bottom: 10px;
    }

    .container__big-card > p {
      font-size: 18px;
      line-height: 1.5;
      text-align: justify;
    }

    .container__small-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .container__small-card {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100%;
      padding: 20px;
      margin: 10px;
      background-color: #f1f1f1;
      border: 1px solid #ddd;
    }

    .container__small-card > h2 {
      font-size: 25px;
      margin-bottom: 10px;
    }

    .container__small-card > p {
      font-size: 18px;
      line-height: 1.5;
      text-align: justify;
    }
  </style>
</head>
<body>
  <app-menu-bar></app-menu-bar>
  <div class="container__menu-title">
    <h1> 
