<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GoPay App</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"/>
  <style>
    /* Global Styles */
    *{margin:0;padding:0;box-sizing:border-box;}
    body{font-family:Arial,sans-serif;background:#fff;}
    .page{display:none;}
    .active{display:block;}

    /* Register/Login Page Styles */
    .help-text{text-align:right;padding:15px 20px;font-size:14px;color:orange;font-weight:bold;}
    .logo-container{margin-top:10px;height:50px;overflow:hidden;position:relative;text-align:center;}
    .logo{display:inline-block;font-size:40px;font-weight:bold;color:#ff4500;animation:moveLogo 1.5s linear infinite alternate;}
    @keyframes moveLogo{0%{transform:translateX(-50px);}100%{transform:translateX(50px);}}
    h2{text-align:center;font-size:18px;margin:20px 0;font-weight:normal;}
    .form-container{width:90%;max-width:350px;margin:0 auto;text-align:center;}
    input{display:block;width:100%;padding:15px;margin:12px 0;border:2px solid green;border-radius:25px;font-size:16px;outline:none;}
    button.register-btn,button.login-btn{background-color:green;color:#fff;font-size:18px;border:none;border-radius:25px;padding:15px;width:100%;cursor:pointer;margin-top:10px;}
    .login-text{margin-top:8px;font-size:12px;color:#333;}
    .login-text a{color:green;font-weight:bold;text-decoration:none;cursor:pointer;}

    /* Dashboard Page Styles */
    body.dashboard-body{background-color:#f5f5f5;overflow-x:hidden;}
    .container{max-width:430px;margin:auto;padding-bottom:50px;}
    .header{display:flex;justify-content:space-between;align-items:center;padding:15px 20px 10px;}
    .profile-info{display:flex;align-items:center;gap:10px;font-weight:bold;color:#333;}
    .profile-icon{width:40px;height:40px;border-radius:50%;background:#ddd;display:flex;justify-content:center;align-items:center;font-size:14px;color:#333;cursor:pointer;}
    .profile-icon.has-image{background-size:cover;background-position:center;background-color:transparent;}
    .profile-icon.has-image .initials{display:none;}
    .profile-icon .initials{font-weight:bold;}
    .bell-icon-container {
      position: relative;
      cursor: pointer;
    }
    .bell-icon{width:32px;height:32px; filter: grayscale(1);}
    .notification-badge{
      position: absolute;
      top: 0;
      right: 0;
      background-color: red;
      color: white;
      border-radius: 50%;
      width: 16px;
      height: 16px;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 10px;
      font-weight: bold;
    }
    .new-dashboard-card{background-color:#28a745;margin:10px 20px;border-radius:18px;color:white;padding:30px 20px;text-align:left;}
    .new-dashboard-card .balance-label{font-size:16px;opacity:0.9;margin-bottom:5px;}
    .new-dashboard-card .balance-amount{font-size:40px;font-weight:bold;margin-bottom:15px;}
    .new-dashboard-card .rewards-info{font-size:16px;opacity:0.9;margin-bottom:30px;}
    .new-dashboard-card .actions{display:flex;justify-content:center;gap:20px;}
    .new-dashboard-card .action-button{background-color:rgba(255,255,255,0.2);border:none;border-radius:25px;color:white;padding:12px 25px;font-size:16px;font-weight:600;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:8px;transition:background-color 0.3s ease;width:150px;}
    .new-dashboard-card .action-button:hover{background-color:rgba(255,255,255,0.3);}
    .new-dashboard-card .action-button img{width:20px;height:20px;filter:invert(100%);}
    .quick-links,.more-links{display:flex;justify-content:space-around;flex-wrap:wrap;padding:0 10px;}
    .link-item{text-align:center;width:70px;margin:10px 5px;cursor:pointer;}
    .link-item img{width:45px;height:45px;margin-bottom:5px;}
    .link-item .label{font-size:13px;color:#333;}
    .promo-banner-side{margin:20px 10px;border-radius:10px;overflow:hidden;position:relative;height:150px;}
    .promo-banner-side img{width:100%;height:100%;object-fit:cover;border-radius:10px;display:block;position:absolute;top:0;right:-100%;animation:slideLeft 15s linear infinite;}
    .promo-banner-side img:nth-child(2){animation-delay:5s;}
    .promo-banner-side img:nth-child(3){animation-delay:10s;}
    @keyframes slideLeft{0%{right:-100%;}10%{right:0%;}33%{right:0%;}43%{right:100%;}100%{right:100%;}}
    
    /* Removed the .whatsapp-support-btn styles */

    /* Transfer Page Styles */
    .transfer-header {
      background-color: #00A859;
      color: white;
      padding: 20px;
      font-size: 20px;
      font-weight: bold;
    }
    .transfer-container {
      padding: 20px;
    }
    .transfer-container h2 {
      margin-bottom: 20px;
      font-size: 22px;
      font-weight: bold;
      color: #000;
      text-align: left; /* Adjusted for this section */
    }
    .transfer-container input, .transfer-container select {
      width: 100%;
      padding: 14px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 10px;
      font-size: 16px;
      box-sizing: border-box;
    }
    .transfer-container select {
      background-color: #fff;
      color: #000;
    }
    .buy-code {
      color: #00A859;
      margin-bottom: 20px;
      font-size: 14px;
      cursor: pointer;
    }
    .balance {
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 30px;
    }
    .submit-btn {
      width: 100%;
      padding: 14px;
      background-color: #00A859;
      color: white;
      border: none;
      font-size: 16px;
      font-weight: bold;
      border-radius: 10px;
      cursor: pointer;
    }
    .submit-btn:hover {
      background-color: #008F4F;
    }

    /* Success page */
    #successPage {
      display: none;
      background-color: #ffffff;
      height: 100vh;
      width: 100vw;
      position: fixed;
      top: 0; left: 0;
      overflow: hidden;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    #successPage .check-circle {
      background-color: #008000;
      color: white;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 40px;
      position: relative;
    }
    #successPage .emoji-burst {
      position: absolute;
      top: -10px;
      right: -10px;
      background-color: #d0f0c0;
      border-radius: 50%;
      padding: 5px;
      font-size: 18px;
    }
    #successPage h1 {
      color: #008000;
      margin-top: 20px;
      font-size: 24px;
    }
    #successPage p {
      margin: 10px;
      font-size: 16px;
      text-align: center;
      max-width: 300px;
    }
    #successPage .success-label {
      background-color: #e6ffe6;
      color: #008000;
      padding: 10px 20px;
      border-radius: 10px;
      font-size: 16px;
      display: flex;
      align-items: center;
      margin-top: 10px;
    }
    #successPage .dashboard-btn {
      background-color: #008000;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 16px;
      border-radius: 10px;
      margin-top: 20px;
      cursor: pointer;
    }
    #flowers {
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      overflow: hidden;
    }
    .flower {
      position: absolute;
      font-size: 24px;
      animation: fly 3s linear infinite;
      opacity: 0;
    }
    @keyframes fly {
      0% { transform: translateY(0) scale(1); opacity: 1; }
      100% { transform: translateY(-600px) scale(1.5); opacity: 0; }
    }

    /* Popup */
    #errorPopup {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.5);
      justify-content: center;
      align-items: center;
    }
    .popup-content {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 90%;
      max-width: 400px;
      text-align: center;
      position: relative;
    }
    .popup-content h3 {
      margin-top: 0;
      color: #000;
    }
    .popup-content p {
      font-size: 14px;
      margin-bottom: 20px;
    }
    .popup-content button {
      background: #00A859;
      color: #fff;
      border: none;
      padding: 12px 20px;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }
    .close-popup {
      position: absolute;
      top: 10px;
      right: 10px;
      font-size: 20px;
      cursor: pointer;
      color: #333;
    }

    /* Profile Page Styles */
    #profilePage header {
      background: #008000; /* green */
      color: #fff;
      padding: 16px;
      display: flex;
      align-items: center;
      font-weight: bold;
      font-size: 18px;
    }
    #profilePage header span {
      margin-left: 8px;
    }
    #profilePage .profile-section {
      text-align: center;
      padding: 24px 16px 16px;
    }
    #profilePage .profile-avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      border: 3px solid #008000;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto;
      font-size: 48px;
      color: #008000;
      background: #f9f9f9;
      cursor:pointer;
    }
    #profilePage .profile-avatar.has-image{background-size:cover;background-position:center;background-color:transparent;}
    #profilePage .profile-avatar.has-image .initials{display:none;}
    #profilePage .profile-avatar .initials{font-weight:bold;}
    #profilePage .profile-name {
      margin-top: 12px;
      font-size: 22px;
      font-weight: bold;
    }
    #profilePage .info-card {
      background: #fff;
      margin: 16px;
      padding: 16px;
      border-radius: 12px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    #profilePage .info-row {
      display: flex;
      align-items: center;
      margin-bottom: 12px;
    }
    #profilePage .info-icon {
      width: 36px;
      height: 36px;
      border-radius: 50%;
      background: #00800022;
      color: #008000;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 10px;
      font-size: 18px;
      flex-shrink: 0;
    }
    #profilePage .info-text {
      display: flex;
      flex-direction: column;
      font-size: 14px;
    }
    #profilePage .info-text span:first-child {
      font-weight: 500;
      color: #666;
    }
    #profilePage .info-text span:last-child {
      font-size: 16px;
      font-weight: bold;
    }
    #profilePage .status-active {
      color: #008000;
    }
    #profilePage .status-not {
      color: #e74c3c;
    }
    #profilePage .logout-btn {
      margin: 20px;
      border: 2px solid #008000;
      color: #008000;
      padding: 12px;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      text-align: center;
      cursor: pointer;
      background: #ffffff;
    }
    #profilePage footer {
      text-align: center;
      padding: 10px;
      background: #f4f4f4;
      color: #444;
      font-size: 13px;
      border-top: 2px solid #008000;
    }

    /* Logout Popup Styles */
    #logoutPopup {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.6);
      justify-content: center;
      align-items: center;
      z-index: 1000;
    }
    .logout-content {
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      width: 90%;
      max-width: 350px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .logout-content h3 {
      margin: 0;
      font-size: 20px;
      color: #333;
    }
    .logout-content p {
      margin: 15px 0 25px;
      color: #666;
      font-size: 15px;
    }
    .logout-buttons {
      display: flex;
      justify-content: space-around;
      gap: 15px;
    }
    .logout-buttons button {
      flex: 1;
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .logout-buttons .yes-btn {
      background-color: #e74c3c;
      color: #fff;
    }
    .logout-buttons .yes-btn:hover {
      background-color: #c0392b;
    }
    .logout-buttons .no-btn {
      background-color: #ecf0f1;
      color: #333;
      border: 1px solid #bdc3c7;
    }
    .logout-buttons .no-btn:hover {
      background-color: #dcdcdc;
    }
    /* NEW STYLE from second code */
    #earnMorePage {
      background-color: #ffffff;
      padding: 20px;
      font-family: Arial, sans-serif;
      text-align: center;
    }
    #earnMorePage h1 {
      color: #000000;
      font-size: 28px;
      margin-top: 40px;
    }
    #earnMorePage p {
      color: #333333;
      font-size: 18px;
      margin: 20px 0;
      line-height: 1.5;
    }
    #earnMorePage .btn {
      background-color: #28a745; /* green */
      color: white;
      border: none;
      padding: 14px 30px;
      font-size: 18px;
      border-radius: 6px;
      cursor: pointer;
      margin: 15px 0;
      text-decoration: none;
      display: inline-block;
    }
    #earnMorePage .btn:hover {
      background-color: #218838;
    }
    #earnMorePage .section {
      margin-bottom: 60px;
    }

    /* NEW STYLES for Join Group Page */
    #joinGroupPage .page-container {
      max-width: 600px;
      width: 100%;
      background-color: #fff;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin: auto;
    }
    #joinGroupPage .header {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }
    #joinGroupPage .back-arrow {
      font-size: 24px;
      color: #333;
      margin-right: 15px;
      cursor: pointer;
    }
    #joinGroupPage .header-title {
      font-size: 18px;
      font-weight: bold;
      color: #333;
    }
    #joinGroupPage .title {
      font-size: 24px;
      font-weight: bold;
      color: #7e22ce;
      margin-bottom: 5px;
    }
    #joinGroupPage .subtitle {
      font-size: 16px;
      color: #666;
      margin-bottom: 25px;
    }
    #joinGroupPage .channel-box {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 15px;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    #joinGroupPage .channel-info {
      display: flex;
      align-items: center;
    }
    #joinGroupPage .icon-container {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background-color: #25d366;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-right: 15px;
    }
    #joinGroupPage .channel-name {
      font-size: 16px;
      font-weight: 500;
      color: #333;
    }
    #joinGroupPage .join-button {
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 12px 20px;
      background-color: #25d366;
      color: #fff;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    #joinGroupPage .join-button:hover {
      background-color: #128c7e;
    }
    #joinGroupPage .join-button .icon {
      margin-right: 8px;
      width: 20px;
      height: 20px;
    }
    #joinGroupPage .join-button .icon svg {
      width: 100%;
      height: 100%;
    }

    /* Notification Page Styles */
    #notificationPage {
      background-color: white;
      color: black;
    }
    #notificationPage .top-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 16px;
      border-bottom: 1px solid #ddd;
    }
    #notificationPage .top-bar .left {
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 16px;
      cursor: pointer;
    }
    #notificationPage .top-bar .right {
      color: red;
      font-size: 16px;
      display: flex;
      align-items: center;
      gap: 4px;
      cursor: pointer;
    }
    #notificationPage .main {
      padding: 20px 16px;
    }
    #notificationPage .main h2 {
      font-size: 18px;
      margin-bottom: 16px;
    }
    #notificationPage .transaction {
      border: 1px solid #e5e7eb;
      border-radius: 8px;
      padding: 12px 16px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 10px;
    }
    #notificationPage .transaction .left {
      display: flex;
      align-items: center;
    }
    #notificationPage .icon {
      width: 36px;
      height: 36px;
      background-color: #d1fae5;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      color: green;
      font-size: 20px;
      margin-right: 12px;
    }
    #notificationPage .desc {
      display: flex;
      flex-direction: column;
    }
    #notificationPage .desc .title {
      font-weight: bold;
      font-size: 16px;
    }
    #notificationPage .desc .time {
      color: gray;
      font-size: 14px;
      margin-top: 4px;
    }
    #notificationPage .amount {
      color: green;
      font-size: 16px;
      font-weight: bold;
    }
    .withdrawal-details {
      font-size: 12px;
      color: #666;
      margin-top: 5px;
      white-space: pre-wrap; /* Preserve line breaks */
    }

    /* BUY AIRTIME PAGE STYLES */
    #airtimePage {
      max-width: 430px;
      width: 100%;
      margin: auto;
      padding: 20px;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: #f0f2f5;
      min-height: 100vh;
    }
    #airtimePage .airtime-header {
      display: flex;
      align-items: center;
      padding: 15px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
    }
    #airtimePage .airtime-promo {
      background-color: #9333ea;
      color: white;
      padding: 15px;
      text-align: center;
      position: relative;
      margin-bottom: 20px;
    }
    #airtimePage .airtime-promo span {
      color: yellow;
      font-weight: bold;
    }
    #airtimePage .airtime-go-button {
      position: absolute;
      right: 15px;
      top: 15px;
      background-color: yellow;
      color: black;
      padding: 6px 18px;
      border-radius: 20px;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
    #airtimePage .airtime-networks {
      display: flex;
      justify-content: space-around;
      margin: 15px 10px;
    }
    #airtimePage .airtime-network {
      border-radius: 15px;
      padding: 5px;
      border: 3px solid transparent;
      cursor: pointer;
    }
    #airtimePage .airtime-network.selected {
      border: 3px solid green;
    }
    #airtimePage .airtime-network img {
      width: 60px;
      height: 60px;
      border-radius: 15px;
    }
    #airtimePage input[type="text"] {
      width: 90%;
      margin: 15px auto;
      padding: 12px;
      display: block;
      font-size: 16px;
      border-radius: 10px;
      border: 1px solid #ccc;
    }
    #airtimePage .airtime-amount-section {
      text-align: left;
      padding: 0 15px;
      font-weight: bold;
    }
    #airtimePage .airtime-amounts {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
      padding: 10px 15px;
    }
    #airtimePage .airtime-amount {
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
      cursor: pointer;
    }
    #airtimePage .airtime-amount.selected {
      border: 2px solid purple;
      background-color: #f3e8ff;
    }
    #airtimePage .airtime-cashback {
      color: gray;
      font-size: 12px;
      margin-top: 4px;
    }
    #airtimePage .airtime-buy-button {
      width: 100%;
      padding: 15px;
      font-size: 18px;
      background-color: #9333ea;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    #airtimePage .airtime-buy-button:hover {
      background-color: #7e22ce;
    }

    /* Airtime Success Styles */
    #airtimeSuccessCard .success-icon-container {
      position: relative;
      width: 100px;
      height: 100px;
      margin: 0 auto 20px;
    }
    #airtimeSuccessCard .icon-circle {
      width: 100px;
      height: 100px;
      background-color: #179357;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 48px;
    }
    #airtimeSuccessCard .status-title {
      font-size: 28px;
      font-weight: 600;
      color: #333;
      margin: 0;
    }
    #airtimeSuccessCard .amount-display {
      font-size: 40px;
      font-weight: 700;
      color: #000;
      margin: 10px 0 30px;
    }
    #airtimeSuccessCard .details-section {
      border-radius: 15px;
      padding: 20px;
      margin-bottom: 30px;
      background-color: transparent;
    }
    #airtimeSuccessCard .bonus-earned {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 10px;
      font-weight: 600;
    }
    #airtimeSuccessCard .bonus-earned .label {
      color: #666;
    }
    #airtimeSuccessCard .bonus-earned .bonus-amount {
      color: #179357;
    }
    #airtimeSuccessCard .cashback-note {
      font-size: 14px;
      color: #999;
    }
    #airtimeSuccessCard .button-group {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    #airtimeSuccessCard .share-button, #airtimeSuccessCard .view-details-button {
      font-size: 18px;
      font-weight: 600;
      padding: 16px;
      border-radius: 15px;
      border: none;
      cursor: pointer;
    }
    #airtimeSuccessCard .share-button {
      background-color: #179357;
      color: #ffffff;
    }
    #airtimeSuccessCard .view-details-button {
      background-color: #e8eaf6;
      color: #333;
    }
    
    /* Airtime Receipt Styles */
    #airtimeReceipt .top-section {
      background: #f9f9f9;
      border-radius: 16px;
      padding: 20px;
      text-align: center;
    }
    #airtimeReceipt .top-section img {
      width: 50px;
      height: 50px;
      margin-bottom: 10px;
      border-radius: 10px;
    }
    #airtimeReceipt .top-section h2 {
      margin: 0;
      font-size: 16px;
      font-weight: 600;
    }
    #airtimeReceipt .top-section .amount-display {
      font-size: 28px;
      font-weight: bold;
      margin-top: 5px;
      margin-bottom: 5px;
    }
    #airtimeReceipt .top-section .status {
      color: #00aa5b;
      font-weight: 600;
      margin-bottom: 8px;
      font-size: 15px;
    }
    #airtimeReceipt .transaction-box {
      background: #f9f9f9;
      border-radius: 16px;
      padding: 18px 16px;
      margin-top: 16px;
      text-align: left;
    }
    #airtimeReceipt .transaction-box .item {
      margin-bottom: 15px;
    }
    #airtimeReceipt .transaction-box .label {
      color: #999;
      font-size: 13px;
    }
    #airtimeReceipt .transaction-box .value {
      font-size: 15px;
      font-weight: 500;
      margin-top: 2px;
      color: #000;
    }
    #airtimeReceipt .button-row {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }
    #airtimeReceipt .btn {
      flex: 1;
      padding: 13px;
      border-radius: 24px;
      font-size: 15px;
      border: none;
      font-weight: 600;
      cursor: pointer;
    }
    #airtimeReceipt .btn:first-child {
      margin-right: 10px;
    }
    #airtimeReceipt .btn-back {
      background-color: #e8f6f0;
      color: #00aa5b;
    }
    #airtimeReceipt .btn-share {
      background-color: #00aa5b;
      color: white;
    }

    /* Airtime Popup Modal Styles */
    .popup-overlay {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
        display: none;
        justify-content: center;
        align-items: center;
        z-index: 1000;
    }

    .popup-card {
        background-color: white;
        border-radius: 15px;
        width: 300px;
        padding: 20px;
        text-align: center;
        position: relative;
    }

    .popup-cancel-icon {
        position: absolute;
        top: 10px;
        right: 15px;
        font-size: 20px;
        cursor: pointer;
        color: #999;
    }

    .popup-title {
        font-size: 20px;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .popup-message {
        margin-bottom: 20px;
        color: #666;
    }

    .popup-button {
        background-color: #00aa5b;
        color: white;
        padding: 10px 20px;
        border-radius: 20px;
        border: none;
        cursor: pointer;
        font-weight: bold;
    }
  </style>
</head>
<body>
  <div id="registerPage" class="page active">
    <div class="help-text">Need Help?</div>
    <div class="logo-container"><div class="logo">GOPAY</div></div>
    <h2>Create your Account</h2>
    <div class="form-container">
      <input id="regName" type="text" placeholder="Full name">
      <input id="regEmail" type="email" placeholder="Email Address">
      <input id="regPass" type="password" placeholder="Password">
      <button class="register-btn" id="registerBtn" onclick="registerUser()">Register</button>
      <div class="login-text">Already have an account? <a onclick="showLogin()">Login</a></div>
    </div>
  </div>

  <div id="loginPage" class="page">
    <div class="help-text">Welcome Back</div>
    <div class="logo-container"><div class="logo">GOPAY</div></div>
    <h2>Login to your Account</h2>
    <div class="form-container">
      <input id="logEmail" type="email" placeholder="Email Address">
      <input id="logPass" type="password" placeholder="Password">
      <button class="login-btn" onclick="loginUser()">Login</button>
      <div class="login-text">Don’t have an account? <a onclick="showRegister()">Register</a></div>
    </div>
  </div>

  <div id="dashboardPage" class="page">
    <div class="container">
      <div class="header">
        <div class="profile-info">
          <div class="profile-icon" id="profileIcon"><span class="initials">U</span></div>
          <span id="profileName"></span>
        </div>
        <div class="bell-icon-container" onclick="showNotificationPage()">
          <img class="bell-icon" src="https://img.icons8.com/emoji/48/bell-emoji.png" alt="Notification" />
          <div class="notification-badge" id="notificationBadge" style="display:none;">1</div>
        </div>
      </div>
      <div class="new-dashboard-card">
        <div class="balance-label">Your Balance</div>
        <div class="balance-amount" id="balanceAmount">₦170,000.00</div>
        <div class="rewards-info">Weekly Rewards: ₦170,000.00</div>
        <div class="actions">
          <button class="action-button"><img src="https://img.icons8.com/ios-filled/50/checked--v1.png"/>Activate</button>
          <button class="action-button" onclick="showTransferPage()"><img src="https://img.icons8.com/ios-filled/50/upload--v1.png"/>Transfer</button>
        </div>
      </div>
      <div class="quick-links">
        <div class="link-item"><img src="https://img.icons8.com/fluency/48/send.png"/><div class="label">Buy code</div></div>
        <div class="link-item"><img src="https://img.icons8.com/color/48/invoice.png"/><div class="label">Data</div></div>
        <div class="link-item" onclick="showAirtimePage()"><img src="https://img.icons8.com/color/48/wifi.png"/><div class="label">Airtime</div></div>
        <div class="link-item"><img src="https://img.icons8.com/fluency/48/add.png"/><div class="label">Favorites</div></div>
      </div>
      <div class="more-links">
        <div class="link-item" onclick="openSupportLink()">
          <img src="https://img.icons8.com/ios-filled/50/headset.png"/>
          <div class="label">Support</div>
        </div>
        <div class="link-item" onclick="showJoinGroupPage()">
          <img src="https://img.icons8.com/color/48/internet.png"/>
          <div class="label">Group</div>
        </div>
        <div class="link-item" onclick="showEarnMorePage()">
          <img src="https://img.icons8.com/emoji/48/money-bag-emoji.png"/>
          <div class="label">Earn More</div>
        </div>
        <div class="link-item" id="bottomProfileIcon"><img src="https://img.icons8.com/color/48/user.png"/><div class="label">Profile</div></div>
      </div>
      <div class="promo-banner-side">
        <img src="https://raw.githubusercontent.com/darkweb765/Mining1/main/IMG-20250723-WA0022.jpg" />
        <img src="https://raw.githubusercontent.com/darkweb765/Mining1/main/IMG-20250723-WA0011.jpg" />
        <img src="https://raw.githubusercontent.com/darkweb765/Mining1/main/IMG-20250721-WA0000.jpg" />
      </div>
      
      </div>
  </div>

  <div id="transferPage" class="page">
    <div class="transfer-header">Transfer To Bank</div>
    <div class="transfer-container">
      <h2>Bank Details</h2>
      <input id="accName" type="text" placeholder="Account Name">
      <input id="accNumber" type="text" placeholder="Account Number (10 digits)">
      <select id="bankSelect">
        <option>Select Bank</option>
        <option>Opay</option>
        <option>PalmPay</option>
        <option>Kuda Bank</option>
        <option>Moniepoint</option>
        <option>FairMoney</option>
        <option>Carbon (formerly Paylater)</option>
        <option>VBank (by VFD Microfinance Bank)</option>
        <option>ALAT by Wema Bank</option>
        <option>Rubies Bank</option>
        <option>Sparkle Bank</option>
        <option>Umba Bank</option>
        <option>Chipper Cash</option>
        <option>Paga</option>
        <option>Paga Bank</option>
        <option>Access Bank</option>
        <option>Zenith Bank</option>
        <option>Guaranty Trust Bank (GTBank)</option>
        <option>First Bank</option>
        <option>United Bank for Africa</option>
        <option>Fidelity Bank</option>
        <option>Union Bank of Nigeria</option>
        <option>Stanbic IBTC Bank</option>
        <option>Sterling Bank</option>
        <option>Wema Bank</option>
        <option>Polaris Bank</option>
        <option>Ecobank Nigeria</option>
        <option>Keystone Bank</option>
        <option>Heritage Bank</option>
        <option>Titan Trust Bank</option>
        <option>Providus Bank</option>
        <option>SunTrust Bank</option>
        <option>Globus Bank</option>
        <option>TAJBank</option>
        <option>Lotus Bank</option>
        <option>Jaiz Bank</option>
        <option>Parallex Bank</option>
        <option>Unity Bank</option>
        <option>Nova Merchant Bank</option>
        <option>FSDH Merchant Bank</option>
        <option>Rand Merchant Bank</option>
        <option>Coronation Merchant Bank</option>
        <option>PremiumTrust Bank</option>
        <option>Optimus Bank</option>
        <option>Signature Bank</option>
      </select>
      <input id="amount" type="text" placeholder="Amount">
      <input id="otpCode" type="text" placeholder="GO  CODE (Buy GO Code)">
      <div class="buy-code">Buy GO code</div>
      <div class="balance">Available Balance: <span id="transferBalance">₦170,000.00</span></div>
      <button class="submit-btn" onclick="submitForm()">Submit</button>
    </div>
  </div>

  <div id="successPage">
    <div class="check-circle">✓<div class="emoji-burst">🎉</div></div>
    <h1>Transfer Successful!</h1>
    <p>Your transfer of ₦<span id="successAmount"></span> has been processed successfully.</p>
    <div class="success-label"><span>🎉</span> Success</div>
    <button class="dashboard-btn" onclick="goBackToDashboard()">Back to Dashboard</button>
    <div id="flowers"></div>
  </div>

  <div id="errorPopup">
    <div class="popup-content">
      <span class="close-popup" onclick="closePopup()">✖</span>
      <h3>Incorrect Go Code</h3>
      <p>The code you entered is incorrect. Click the button below to buy your go codes.</p>
      <button onclick="alert('Redirecting to buy codes...')">Buy Go Codes</button>
    </div>
  </div>

  <div id="profilePage" class="page">
    <header>
      <div style="font-size:20px;cursor:pointer;" onclick="showDashboard()">←</div>
      <span>Profile Information</span>
    </header>
    <div class="profile-section">
      <div class="profile-avatar" id="profileAvatar"><span class="initials">👤</span></div>
      <div class="profile-name" id="profilePageName"></div>
    </div>
    <div class="info-card">
      <div class="info-row">
        <div class="info-icon">👤</div>
        <div class="info-text">
          <span>Full Name</span>
          <span id="profileFullName"></span>
        </div>
      </div>
      <div class="info-row">
        <div class="info-icon">✉️</div>
        <div class="info-text">
          <span>Email Address</span>
          <span id="profileEmail"></span>
        </div>
      </div>
      <div class="info-row">
        <div class="info-icon">⭐</div>
        <div class="info-text">
          <span>Account Level</span>
          <span>Basic</span>
        </div>
      </div>
      <div class="info-row">
        <div class="info-icon">✔️</div>
        <div class="info-text">
          <span>Account Status</span>
          <span class="status-active">Active</span>
        </div>
      </div>
      <div class="info-row">
        <div class="info-icon">GO</div>
        <div class="info-text">
          <span>Go code Status</span>
          <span class="status-not">Not Purchased</span>
        </div>
      </div>
    </div>
    <div class="logout-btn" onclick="logoutUser()">Logout</div>
    <footer>
    </footer>
  </div>

  <div id="logoutPopup">
    <div class="logout-content">
      <h3>Are you sure?</h3>
      <p>You will be logged out of your account.</p>
      <div class="logout-buttons">
        <button class="yes-btn" onclick="confirmLogout(true)">Yes, Logout</button>
        <button class="no-btn" onclick="confirmLogout(false)">No, Stay</button>
      </div>
    </div>
  </div>

  <div id="earnMorePage" class="page">
    <div style="text-align: left; padding: 20px;">
        <button onclick="showDashboard()" style="background: none; border: none; font-size: 20px; cursor: pointer;">←</button>
    </div>
    <div class="section">
      <h1>Register on Daily Pay</h1>
      <p>
        Start earning more money today!<br>
        Sign up on the Daily Pay app now and get started.<br>
        Click the button below to sign up!
      </p>
      <a class="btn" onclick="openInBrowser('https://daily-pay1.vercel.app')">Sign Up</a>
    </div>
    <div class="section">
      <h1>Login into Miner Cash</h1>
      <p>
        If you want to earn up to ₦250,000 daily, sign up on Miner Cash now to start mining!
      </p>
      <a class="btn" onclick="openInBrowser('https://minercash1.vercel.app/')">Sign Up</a>
    </div>
  </div>

  <div id="joinGroupPage" class="page">
    <div class="page-container">
      <div class="header">
        <span class="back-arrow" onclick="showDashboard()">&larr;</span>
        <span class="header-title">Join Our Communities</span>
      </div>
      <h2 class="title">Connect With Us</h2>
      <p class="subtitle">Join our official channels for updates and support.</p>
      <div class="channel-box">
        <div class="channel-info">
          <div class="icon-container">
            <div class="icon">
              <svg fill="white" viewBox="0 0 32 32">
                <path d="M16 2.938a13.06 13.06 0 0 0-11.367 19.648l-1.406 5.148 5.289-1.375A13.053 13.053 0 1 0 16 2.937zm7.693 18.74c-.324.91-1.893 1.75-2.621 1.867-.676.102-1.504.145-2.434-.153-.56-.178-1.274-.414-2.195-.813-3.861-1.671-6.386-5.535-6.58-5.8-.192-.266-1.572-2.092-1.572-3.99s.994-2.829 1.346-3.214c.353-.388.77-.484 1.026-.484.256 0 .513.002.736.013.24.012.555-.045.867.66.334.764 1.132 2.648 1.234 2.84.102.19.172.416.032.682-.14.266-.211.416-.414.64-.204.224-.436.498-.62.67-.204.19-.416.397-.18.78.234.388 1.037 1.712 2.23 2.773 1.534 1.358 2.83 1.77 3.217 1.963.388.192.61.16.835-.096.224-.256.96-1.12 1.218-1.504.256-.388.512-.32.867-.192.353.128 2.244 1.057 2.621 1.248.38.192.637.288.736.448.096.153.096.892-.228 1.8z"/>
              </svg>
            </div>
          </div>
          <span class="channel-name">WhatsApp Channel</span>
        </div>
        <a href="https://whatsapp.com/channel/0029VbB3jUz9WtBzGVpW5K3k" class="join-button" target="_blank">
          <div class="icon">
            <svg fill="white" viewBox="0 0 32 32">
              <path d="M16 2.938a13.06 13.06 0 0 0-11.367 19.648l-1.406 5.148 5.289-1.375A13.053 13.053 0 1 0 16 2.937zm7.693 18.74c-.324.91-1.893 1.75-2.621 1.867-.676.102-1.504.145-2.434-.153-.56-.178-1.274-.414-2.195-.813-3.861-1.671-6.386-5.535-6.58-5.8-.192-.266-1.572-2.092-1.572-3.99s.994-2.829 1.346-3.214c.353-.388.77-.484 1.026-.484.256 0 .513.002.736.013.24.012.555-.045.867.66.334.764 1.132 2.648 1.234 2.84.102.19.172.416.032.682-.14.266-.211.416-.414.64-.204.224-.436.498-.62.67-.204.19-.416.397-.18.78.234.388 1.037 1.712 2.23 2.773 1.534 1.358 2.83 1.77 3.217 1.963.388.192.61.16.835-.096.224-.256.96-1.12 1.218-1.504.256-.388.512-.32.867-.192.353.128 2.244 1.057 2.621 1.248.38.192.637.288.736.448.096.153.096.892-.228 1.8z"/>
            </svg>
          </div>
          Join WhatsApp
        </a>
      </div>
      <div class="channel-box">
        <div class="channel-info">
          <div class="icon-container">
            <div class="icon">
              <svg fill="white" viewBox="0 0 32 32">
                <path d="M16 2.938a13.06 13.06 0 0 0-11.367 19.648l-1.406 5.148 5.289-1.375A13.053 13.053 0 1 0 16 2.937zm7.693 18.74c-.324.91-1.893 1.75-2.621 1.867-.676.102-1.504.145-2.434-.153-.56-.178-1.274-.414-2.195-.813-3.861-1.671-6.386-5.535-6.58-5.8-.192-.266-1.572-2.092-1.572-3.99s.994-2.829 1.346-3.214c.353-.388.77-.484 1.026-.484.256 0 .513.002.736.013.24.012.555-.045.867.66.334.764 1.132 2.648 1.234 2.84.102.19.172.416.032.682-.14.266-.211.416-.414.64-.204.224-.436.498-.62.67-.204.19-.416.397-.18.78.234.388 1.037 1.712 2.23 2.773 1.534 1.358 2.83 1.77 3.217 1.963.388.192.61.16.835-.096.224-.256.96-1.12 1.218-1.504.256-.388.512-.32.867-.192.353.128 2.244 1.057 2.621 1.248.38.192.637.288.736.448.096.153.096.892-.228 1.8z"/>
            </svg>
            </div>
          </div>
          <span class="channel-name">WhatsApp Group</span>
        </div>
        <a href="https://chat.whatsapp.com/I6sKYQk5ftp1VsWkGFIgF6?mode=ac_t" class="join-button" target="_blank">
          <div class="icon">
            <svg fill="white" viewBox="0 0 32 32">
              <path d="M16 2.938a13.06 13.06 0 0 0-11.367 19.648l-1.406 5.148 5.289-1.375A13.053 13.053 0 1 0 16 2.937zm7.693 18.74c-.324.91-1.893 1.75-2.621 1.867-.676.102-1.504.145-2.434-.153-.56-.178-1.274-.414-2.195-.813-3.861-1.671-6.386-5.535-6.58-5.8-.192-.266-1.572-2.092-1.572-3.99s.994-2.829 1.346-3.214c.353-.388.77-.484 1.026-.484.256 0 .513.002.736.013.24.012.555-.045.867.66.334.764 1.132 2.648 1.234 2.84.102.19.172.416.032.682-.14.266-.211.416-.414.64-.204.224-.436.498-.62.67-.204.19-.416.397-.18.78.234.388 1.037 1.712 2.23 2.773 1.534 1.358 2.83 1.77 3.217 1.963.388.192.61.16.835-.096.224-.256.96-1.12 1.218-1.504.256-.388.512-.32.867-.192.353.128 2.244 1.057 2.621 1.248.38.192.637.288.736.448.096.153.096.892-.228 1.8z"/>
            </svg>
          </div>
          Join WhatsApp Group
        </a>
      </div>
    </div>
  </div>

  <div id="notificationPage" class="page">
    <div class="top-bar">
      <div class="left" onclick="showDashboard()">← Transaction History</div>
      <div class="right" onclick="clearTransactions()">🗑️ Clear</div>
    </div>
    <div class="main">
      <h2>Your Transactions</h2>
      <div id="transactionList">
        <div class="transaction">
          <div class="left">
            <div class="icon">🎁</div>
            <div class="desc">
              <div class="title">Welcome Bonus</div>
              <div class="time">Jul 20, 2025 at 10:43 PM</div>
            </div>
          </div>
          <div class="amount">+₦180,000.00</div>
        </div>
      </div>
    </div>
  </div>

  <div id="airtimePage" class="page">
    <div class="airtime-header" onclick="showDashboard()">← Airtime</div>
    <div class="airtime-promo">
      Enjoy <span>Airtime Bonuses!</span>
      <button class="airtime-go-button">GO</button>
    </div>
    <div class="airtime-networks">
      <div class="airtime-network" data-name="MTN" onclick="selectNetwork(this, 'MTN', 'https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0001.jpg')">
        <img src="https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0001.jpg" alt="MTN Logo">
      </div>
      <div class="airtime-network" data-name="Airtel" onclick="selectNetwork(this, '9 mobile', 'https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0003.jpg')">
        <img src="https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0003.jpg" alt="Airtel Logo">
      </div>
      <div class="airtime-network" data-name="9Mobile" onclick="selectNetwork(this, 'GLO', 'https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0004.jpg')">
        <img src="https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0004.jpg" alt="9Mobile Logo">
      </div>
      <div class="airtime-network" data-name="GLO" onclick="selectNetwork(this, 'Airtel', 'https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0002.jpg')">
        <img src="https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0002.jpg" alt="GLO Logo">
      </div>
    </div>

    <input type="text" placeholder="Enter mobile number" id="mobileNumberInput">

    <div class="airtime-amount-section">Select Amount</div>
    <div class="airtime-amounts">
      <div class="airtime-amount" data-amount="50" data-cashback="1" onclick="selectAmount(this)">₦50 <div class="airtime-cashback">₦1 Cashback</div></div>
      <div class="airtime-amount" data-amount="100" data-cashback="2" onclick="selectAmount(this)">₦100 <div class="airtime-cashback">₦2 Cashback</div></div>
      <div class="airtime-amount selected" data-amount="200" data-cashback="3" onclick="selectAmount(this)">₦200 <div class="airtime-cashback">₦3 Cashback</div></div>
      <div class="airtime-amount" data-amount="500" data-cashback="10" onclick="selectAmount(this)">₦500 <div class="airtime-cashback">₦10 Cashback</div></div>
      <div class="airtime-amount" data-amount="1000" data-cashback="20" onclick="selectAmount(this)">₦1000 <div class="airtime-cashback">₦20 Cashback</div></div>
      <div class="airtime-amount" data-amount="2000" data-cashback="50" onclick="selectAmount(this)">₦2000 <div class="airtime-cashback">₦50 Cashback</div></div>
      <div class="airtime-amount" data-amount="3000" data-cashback="75" onclick="selectAmount(this)">₦3000 <div class="airtime-cashback">₦75 Cashback</div></div>
      <div class="airtime-amount" data-amount="5000" data-cashback="125" onclick="selectAmount(this)">₦5000 <div class="airtime-cashback">₦125 Cashback</div></div>
      <div class="airtime-amount" data-amount="10000" data-cashback="250" onclick="selectAmount(this)">₦10000 <div class="airtime-cashback">₦250 Cashback</div></div>
    </div>

    <input type="text" placeholder="Enter GO Code" id="goCodeInput">

    <button class="airtime-buy-button" onclick="handleBuyAirtime()">Buy Airtime</button>
  </div>
  
  <div class="page" id="airtimeSuccessCard">
    <div class="container">
      <div class="success-icon-container">
        <div class="icon-circle">
          <i class="fas fa-check"></i>
        </div>
      </div>
      <h1 class="status-title">Airtime Purchase Successful</h1>
      <p class="amount-display" id="airtimeSuccessAmountDisplay">₦0.00</p>
      <div class="details-section">
        <div class="bonus-earned">
          <span class="label">Bonus Earned</span>
          <span class="bonus-amount" id="airtimeSuccessCashbackDisplay">+₦0.00 Cashback</span>
        </div>
        <div class="cashback-note" id="airtimeSuccessCashbackNote">
          ₦0.00 Cashback
        </div>
      </div>
      <div class="button-group">
        <button class="share-button">Share Receipt</button>
        <button class="view-details-button" onclick="showDetails()">View Details</button>
      </div>
    </div>
  </div>
  
  <div class="page" id="airtimeReceipt">
    <div class="container">
      <div class="top-section">
        <img id="receiptNetworkIcon" src="" alt="Network Logo">
        <h2 id="receiptNetworkName"></h2>
        <div class="amount-display" id="receiptAmountDisplay">₦0.00</div>
        <div class="status">✔ Successful</div>
        <div class="bonus-earned-receipt">Bonus Earned</div>
        <div class="cashback-receipt" id="receiptCashbackDisplay">+₦0.00 Cashback</div>
      </div>
      <div class="transaction-box">
        <div class="item">
          <div class="label">Recipient Mobile</div>
          <div class="value" id="receiptMobileNumber"></div>
        </div>
        <div class="item">
          <div class="label">Transaction Type</div>
          <div class="value">Airtime</div>
        </div>
        <div class="item">
          <div class="label">Payment Method</div>
          <div class="value">OWealth</div>
        </div>
        <div class="item">
          <div class="label">Transaction No.</div>
          <div class="value">250802120100180463710243</div>
        </div>
        <div class="item">
          <div class="label">Transaction Date</div>
          <div class="value">Aug 2nd, 2025 12:01:19 PM</div>
        </div>
      </div>
      <div class="button-row">
        <button class="btn btn-back" onclick="goBackToAirtimeForm()">Back</button>
        <button class="btn btn-share">Share Receipt</button>
      </div>
    </div>
  </div>

  <div class="popup-overlay" id="airtimeGoCodePopup">
    <div class="popup-card">
      <span class="popup-cancel-icon" onclick="hideAirtimePopup()">&times;</span>
      <div class="popup-title">Incorrect GO code</div>
      <div class="popup-message">You have entered an invalid GO code.</div>
      <button class="popup-button" onclick="hideAirtimePopup()">Buy GO Code</button>
    </div>
  </div>

  <input type="file" id="imageUpload" accept="image/*" style="display: none;" />

  <script>
    // Initial balance setup (saved in local storage)
    let balance = localStorage.getItem('gopayBalance') ? parseFloat(localStorage.getItem('gopayBalance')) : 170000;
    
    // Airtime purchase variables
    let selectedNetworkIconSrc = 'https://raw.githubusercontent.com/darkweb765/Opaypay/main/IMG-20250802-WA0001.jpg'; // Default to MTN
    let selectedNetworkName = 'MTN'; // Default to MTN
    let selectedAmount = '200';
    let selectedCashback = '3';
    let selectedMobileNumber = '';

    // Check for new notifications on app load
    document.addEventListener('DOMContentLoaded', () => {
        const notifications = JSON.parse(localStorage.getItem('gopayNotifications')) || [];
        if (notifications.length > 0) {
            document.getElementById('notificationBadge').style.display = 'flex';
        }
        
        // Set default selected network for airtime page
        const defaultNetwork = document.querySelector('.airtime-network[data-name="MTN"]');
        if (defaultNetwork) {
          defaultNetwork.classList.add('selected');
        }
        
        const defaultAmount = document.querySelector('.airtime-amount[data-amount="200"]');
        if (defaultAmount) {
          defaultAmount.classList.add('selected');
        }
    });

    function hideAllPages() {
      document.querySelectorAll('.page').forEach(page => page.classList.remove('active'));
    }

    function showLogin(){
      hideAllPages();
      document.getElementById('registerPage').classList.remove('active');
      document.getElementById('loginPage').classList.add('active');
    }

    function showRegister(){
      hideAllPages();
      document.getElementById('loginPage').classList.remove('active');
      document.getElementById('registerPage').classList.add('active');
    }
    
    function showDashboard(){
      hideAllPages();
      document.getElementById('dashboardPage').classList.add('active');
      updateBalanceDisplay();
      // Remove notification badge when the user goes back to the dashboard from the notification screen
      document.getElementById('notificationBadge').style.display = 'none';
    }

    function showProfilePage() {
      hideAllPages();
      document.getElementById('profilePage').classList.add('active');

      const name = localStorage.getItem('gopayUser');
      const email = localStorage.getItem('gopayEmail');
      const profileImage = localStorage.getItem('gopayProfileImage');
      
      if (name) {
        document.getElementById('profileAvatar').querySelector('.initials').innerText = name.charAt(0).toUpperCase();
        document.getElementById('profilePageName').innerText = name;
        document.getElementById('profileFullName').innerText = name;
      }
      if (email) {
        document.getElementById('profileEmail').innerText = email;
      }
      if(profileImage){
        document.getElementById('profileAvatar').style.backgroundImage = `url(${profileImage})`;
        document.getElementById('profileAvatar').classList.add('has-image');
      } else {
        document.getElementById('profileAvatar').style.backgroundImage = 'none';
        document.getElementById('profileAvatar').classList.remove('has-image');
      }
    }

    function registerUser(){
      const name = document.getElementById('regName').value.trim();
      const email = document.getElementById('regEmail').value.trim();
      const pass = document.getElementById('regPass').value.trim();

      if(!name || !email || !pass){
        alert('Please fill in all fields.');
        return;
      }

      const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      if(!emailRegex.test(email)){
        alert('Please enter a valid email.');
        return;
      }

      const btn = document.getElementById('registerBtn');
      btn.disabled = true;
      btn.innerText = "Registering...";

      setTimeout(() => {
        btn.innerText = "Registered Successfully!";
        localStorage.setItem('gopayUser', name);
        localStorage.setItem('gopayEmail', email);

        setTimeout(() => {
          hideAllPages();
          document.getElementById('dashboardPage').classList.add('active');

          document.getElementById('profileIcon').querySelector('.initials').innerText = name.charAt(0).toUpperCase();
          document.getElementById('profileName').innerText = name;

          btn.innerText = "Register";
          btn.disabled = false;
          // Set initial balance
          localStorage.setItem('gopayBalance', 170000);
          updateBalanceDisplay();
        }, 2000);
      }, 2000);
    }

    function loginUser(){
      const email = document.getElementById('logEmail').value.trim();
      const pass = document.getElementById('logPass').value.trim();
      if(!email || !pass){
        alert('Enter email and password');
        return;
      }
      
      localStorage.setItem('gopayEmail', email);
      hideAllPages();
      document.getElementById('dashboardPage').classList.add('active');
      const storedName = localStorage.getItem('gopayUser') || 'User';
      const profileImage = localStorage.getItem('gopayProfileImage');

      document.getElementById('profileIcon').querySelector('.initials').innerText = storedName.charAt(0).toUpperCase();
      document.getElementById('profileName').innerText = storedName;
      if(profileImage){
        document.getElementById('profileIcon').style.backgroundImage = `url(${profileImage})`;
        document.getElementById('profileIcon').classList.add('has-image');
      }
      updateBalanceDisplay();
    }

    function showTransferPage() {
      hideAllPages();
      document.getElementById('transferPage').classList.add('active');
      updateTransferBalanceDisplay();
    }
    
    function updateTransferBalanceDisplay() {
      document.getElementById('transferBalance').innerText = `₦${balance.toFixed(2).replace(/\d(?=(\d{3})+\.)/g, '$&,')}`;
    }

    function submitForm() {
      const accName = document.getElementById('accName').value.trim();
      const accNumber = document.getElementById('accNumber').value.trim();
      const bankName = document.getElementById('bankSelect').value;
      const amount = document.getElementById('amount').value.trim();
      const enteredCode = document.getElementById('otpCode').value.trim();

      const numericAmount = parseFloat(amount);

      if (!accName || !accNumber || bankName === 'Select Bank' || !amount || !enteredCode) {
          alert('Please fill in all withdrawal details.');
          return;
      }

      if (!/^[0-9]{10}$/.test(accNumber)) {
        alert("Please enter a valid 10-digit account number.");
        return;
      }
      
      if (numericAmount > balance) {
        alert("Insufficient balance for this withdrawal.");
        return;
      }
      
      if (enteredCode === 'OTP35171') {
        // Update balance and save to local storage
        balance -= numericAmount;
        localStorage.setItem('gopayBalance', balance);
        
        // Add new notification
        const withdrawalDetails = {
            amount: numericAmount,
            accName: accName,
            accNumber: accNumber,
            bankName: bankName,
            time: new Date().toLocaleString()
        };
        addWithdrawalNotification(withdrawalDetails);

        document.getElementById('successAmount').innerText = numericAmount.toFixed(2).replace(/\d(?=(\d{3})+\.)/g, '$&,');
        hideAllPages();
        document.getElementById('successPage').style.display = 'flex';
        setInterval(createFlower, 300);
      } else {
        document.getElementById('errorPopup').style.display = 'flex';
      }
    }

    function closePopup() {
      document.getElementById('errorPopup').style.display = 'none';
    }

    function goBackToDashboard() {
      document.getElementById('successPage').style.display = 'none';
      document.getElementById('dashboardPage').classList.add('active');
      updateBalanceDisplay();
      
      // Reset transfer form
      document.getElementById('accName').value = '';
      document.getElementById('accNumber').value = '';
      document.getElementById('bankSelect').value = 'Select Bank';
      document.getElementById('amount').value = '';
      document.getElementById('otpCode').value = '';
    }
    
    function logoutUser() {
      document.getElementById('logoutPopup').style.display = 'flex';
    }

    function confirmLogout(isConfirmed) {
      document.getElementById('logoutPopup').style.display = 'none';
      if (isConfirmed) {
        localStorage.removeItem('gopayUser');
        localStorage.removeItem('gopayEmail');
        localStorage.removeItem('gopayProfileImage');
        localStorage.removeItem('gopayBalance');
        localStorage.removeItem('gopayNotifications');
        hideAllPages();
        document.getElementById('registerPage').classList.add('active');
      }
    }

    function openSupportLink() {
      window.open('https://wa.me/2348076204969?text=Sir%20I%20need%20help%20in%20my%20Go%20Pay%20account', '_blank');
    }

    function createFlower() {
      const flower = document.createElement("div");
      flower.classList.add("flower");
      flower.textContent = "🎉";
      flower.style.left = Math.random() * 100 + "vw";
      flower.style.top = "100vh";
      document.getElementById('flowers').appendChild(flower);
      setTimeout(() => flower.remove(), 3000);
    }
    
    // NEW FUNCTIONALITY: Show the Join Group page
    function showJoinGroupPage() {
      hideAllPages();
      document.getElementById('joinGroupPage').classList.add('active');
    }

    // NEW FUNCTIONALITY: Show the Earn More Page
    function showEarnMorePage() {
      hideAllPages();
      document.getElementById('earnMorePage').classList.add('active');
    }
    
    // NEW FUNCTIONALITY: Function from second code to open links
    function openInBrowser(url) {
      window.open(url, '_blank');
    }
    
    // NEW FUNCTIONALITY: Profile image upload
    function handleProfileImageUpload(event) {
      const file = event.target.files[0];
      if (file) {
        const reader = new FileReader();
        reader.onload = function(e) {
          const imageUrl = e.target.result;
          localStorage.setItem('gopayProfileImage', imageUrl);
          updateProfileImages(imageUrl);
        };
        reader.readAsDataURL(file);
      }
    }

    function updateProfileImages(imageUrl) {
        const profileIcon = document.getElementById('profileIcon');
        const profileAvatar = document.getElementById('profileAvatar');
        
        profileIcon.style.backgroundImage = `url(${imageUrl})`;
        profileIcon.classList.add('has-image');
        
        profileAvatar.style.backgroundImage = `url(${imageUrl})`;
        profileAvatar.classList.add('has-image');
    }
    
    function updateBalanceDisplay() {
        const formattedBalance = balance.toFixed(2).replace(/\d(?=(\d{3})+\.)/g, '$&,');
        document.getElementById('balanceAmount').innerText = `₦${formattedBalance}`;
        document.getElementById('transferBalance').innerText = `₦${formattedBalance}`;
    }

    // NEW FUNCTIONALITY: Notification Screen
    function showNotificationPage() {
        hideAllPages();
        document.getElementById('notificationPage').classList.add('active');
        document.getElementById('notificationBadge').style.display = 'none'; // Hide badge once opened
        loadNotifications();
    }

    function addWithdrawalNotification(details) {
        let notifications = JSON.parse(localStorage.getItem('gopayNotifications')) || [];
        const newNotification = {
            type: 'withdrawal',
            icon: '✅',
            title: 'Withdrawal Successful',
            amount: details.amount,
            account: {
                name: details.accName,
                number: details.accNumber,
                bank: details.bankName,
            },
            time: details.time
        };
        notifications.unshift(newNotification); // Add to the beginning of the array
        localStorage.setItem('gopayNotifications', JSON.stringify(notifications));
        document.getElementById('notificationBadge').style.display = 'flex';
    }
    
    function loadNotifications() {
      const transactionList = document.getElementById('transactionList');
      let notifications = JSON.parse(localStorage.getItem('gopayNotifications')) || [];
      
      // Clear previous notifications, but keep the welcome bonus
      transactionList.innerHTML = `
        <div class="transaction">
          <div class="left">
            <div class="icon">🎁</div>
            <div class="desc">
              <div class="title">Welcome Bonus</div>
              <div class="time">Jul 20, 2025 at 10:43 PM</div>
            </div>
          </div>
          <div class="amount">+₦170,000.00</div>
        </div>
      `;
      
      notifications.forEach(note => {
        if (note.type === 'withdrawal') {
          const newTransaction = document.createElement('div');
          newTransaction.className = 'transaction';
          newTransaction.innerHTML = `
            <div class="left">
              <div class="icon">${note.icon}</div>
              <div class="desc">
                <div class="title">${note.title}</div>
                <div class="time">${note.time}</div>
                <div class="withdrawal-details">
                  Amount: ₦${note.amount.toFixed(2).replace(/\d(?=(\d{3})+\.)/g, '$&,')}\n
                  Account Name: ${note.account.name}\n
                  Account Number: ${note.account.number}\n
                  Bank: ${note.account.bank}
                </div>
              </div>
            </div>
            <div class="amount" style="color: red;">-₦${note.amount.toFixed(2).replace(/\d(?=(\d{3})+\.)/g, '$&,')}</div>
          `;
          transactionList.appendChild(newTransaction);
        }
      });
    }

    function clearTransactions() {
      if (confirm('Are you sure you want to clear all transactions?')) {
        // Clear all notifications except the welcome bonus
        localStorage.removeItem('gopayNotifications');
        loadNotifications();
      }
    }
    
    // NEW FUNCTIONALITY: Airtime Page
    function showAirtimePage() {
      hideAllPages();
      document.getElementById('airtimePage').classList.add('active');
    }

    function selectNetwork(element, name, imgSrc) {
      document.querySelectorAll('.airtime-network').forEach(el => el.classList.remove('selected'));
      element.classList.add('selected');
      selectedNetworkIconSrc = imgSrc;
      selectedNetworkName = name;
    }

    function selectAmount(element) {
      document.querySelectorAll('.airtime-amount').forEach(el => el.classList.remove('selected'));
      element.classList.add('selected');
      selectedAmount = element.getAttribute('data-amount');
      selectedCashback = element.getAttribute('data-cashback');
    }

    function handleBuyAirtime() {
      const goCodeInput = document.getElementById('goCodeInput').value;
      selectedMobileNumber = document.getElementById('mobileNumberInput').value;
      const numericAmount = parseFloat(selectedAmount);

      if (numericAmount > balance) {
        alert("Insufficient balance for this purchase.");
        return;
      }
      
      const correctGoCode = "OTP351"; // This is the placeholder code from the original airtime code. You can change this.

      if (goCodeInput === correctGoCode) {
        // Deduct from balance
        balance -= numericAmount;
        localStorage.setItem('gopayBalance', balance);
        
        hideAllPages();
        document.getElementById('airtimeSuccessCard').classList.add('active');

        document.getElementById('airtimeSuccessAmountDisplay').innerText = `₦${parseFloat(selectedAmount).toFixed(2)}`;
        document.getElementById('airtimeSuccessCashbackDisplay').innerText = `+₦${parseFloat(selectedCashback).toFixed(2)} Cashback`;
        document.getElementById('airtimeSuccessCashbackNote').innerText = `₦${parseFloat(selectedCashback).toFixed(2)} Cashback`;
        
      } else {
        showAirtimePopup();
      }
    }
    
    function showAirtimePopup() {
      document.getElementById('airtimeGoCodePopup').style.display = 'flex';
    }

    function hideAirtimePopup() {
      document.getElementById('airtimeGoCodePopup').style.display = 'none';
    }

    function showDetails() {
      hideAllPages();
      document.getElementById('airtimeReceipt').classList.add('active');

      document.getElementById('receiptNetworkIcon').src = selectedNetworkIconSrc;
      document.getElementById('receiptNetworkIcon').alt = `${selectedNetworkName} Icon`;
      document.getElementById('receiptNetworkName').innerText = selectedNetworkName;
      document.getElementById('receiptAmountDisplay').innerText = `₦${parseFloat(selectedAmount).toFixed(2)}`;
      document.getElementById('receiptCashbackDisplay').innerText = `+₦${parseFloat(selectedCashback).toFixed(2)} Cashback`;
      document.getElementById('receiptMobileNumber').innerText = selectedMobileNumber;
    }

    function goBackToAirtimeForm() {
      hideAllPages();
      document.getElementById('airtimePage').classList.add('active');
    }

    // Event listeners
    document.getElementById('bottomProfileIcon').addEventListener('click', showProfilePage);
    document.getElementById('profileIcon').addEventListener('click', () => {
      document.getElementById('imageUpload').click();
    });
    document.getElementById('profileAvatar').addEventListener('click', () => {
      document.getElementById('imageUpload').click();
    });
    document.getElementById('imageUpload').addEventListener('change', handleProfileImageUpload);
    document.querySelector('.bell-icon-container').addEventListener('click', showNotificationPage);
  </script>
</body>
</html>
