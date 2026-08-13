<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">

<meta name="google-site-verification"
content="6NRcuqiiN2jqKtLXF_zQQ7kt9oQhHYJHMKnIG1w5PU8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sigeon World 🐦</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: #050505;
  color: white;
  font-family: Arial, sans-serif;
}

/* TOP BAR */

header {
  height: 65px;
  background: #101010;
  border-bottom: 1px solid #292929;
  display: flex;
  align-items: center;
  padding: 0 18px;
  gap: 18px;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.menuButton {
  background: transparent;
  border: 0;
  color: white;
  font-size: 30px;
  cursor: pointer;
}

/* COINS */

.coins {
  margin-left: auto;
  background: #151515;
  border: 1px solid #333;
  padding: 9px 14px;
  border-radius: 20px;
  font-weight: bold;
}

.blueCoin {
  color: #249cff;
}

/* SIDE MENU */

.sideMenu {
  position: fixed;
  top: 65px;
  left: -300px;
  width: 280px;
  height: calc(100vh - 65px);
  background: #0c0c0c;
  border-right: 1px solid #292929;
  padding: 15px;
  transition: left 0.3s;
  z-index: 99;
  overflow-y: auto;
}

.sideMenu.open {
  left: 0;
}

.menuItem {
  width: 100%;
  background: #151515;
  color: white;
  border: 1px solid #292929;
  border-radius: 10px;
  padding: 13px;
  margin-bottom: 8px;
  text-align: left;
  cursor: pointer;
  font-size: 15px;
}

.menuItem:hover {
  background: #222;
}

/* MAIN */

main {
  max-width: 1000px;
  margin: auto;
  padding: 25px;
}

.page {
  display: none;
}

.page.active {
  display: block;
}

.card {
  background: #111;
  border: 1px solid #292929;
  border-radius: 17px;
  padding: 25px;
  margin-bottom: 20px;
}

/* HOME */

.hero {
  text-align: center;
  padding: 50px 20px;
}

.pigeon {
  font-size: 90px;
  animation: fly 2s infinite alternate;
}

@keyframes fly {
  from {
    transform: translateX(-30px) rotate(-4deg);
  }
  to {
    transform: translateX(30px) rotate(4deg);
  }
}

.hero h1 {
  font-size: 42px;
}

/* INPUTS */

input,
textarea {
  width: 100%;
  background: #191919;
  color: white;
  border: 1px solid #3a3a3a;
  border-radius: 10px;
  padding: 13px;
  margin-top: 8px;
  margin-bottom: 12px;
  outline: none;
}

textarea {
  min-height: 120px;
  resize: vertical;
}

/* BUTTONS */

.button {
  background: white;
  color: black;
  border: 0;
  border
