---
layout: page
title: "Future Plans"
permalink: /future-plans/
---

<div class="bucket-list-container">
  <div class="bucket-section">
    <h3 class="bucket-subtitle">Physical Challenge Bucket List</h3>
    <ul class="clean-bucket-list">
      <li><span class="checkbox-box"></span>Cycle to Egypt</li>
      <li><span class="checkbox-box"></span>Complete the Welsh 3000s (3 weekends?)</li>
      <li><span class="checkbox-box"></span>Spend a year ticking off the Wainwrights</li>
      <li><span class="checkbox-box"></span>Walk Offa's Dyke</li>
      <li><span class="checkbox-box"></span>Mountain Bike the Continental Divide</li>
      <li><span class="checkbox-box"></span>Walk the Dales Way</li>
      <li><span class="checkbox-box"></span>Cycle Pan American Highway</li>
      <li><span class="checkbox-box"></span>Walk the South Downs Way</li>
      <li><span class="checkbox-box"></span>Walk the Pennine Way</li>
      <li><span class="checkbox-box"></span>Canoe Devizes to Westminster</li>
      <li><span class="checkbox-box"></span>Complete the Welsh Hewitts</li>
      <li><span class="checkbox-box"></span>Cycle Royal Chilterns Cycleway</li>
       <li><span class="checkbox-box"></span>Walk the Lycian Way</li>
    </ul>
  </div>

  <div class="bucket-section">
    <h3 class="bucket-subtitle">Recreational Bucket List</h3>
    <ul class="clean-bucket-list">
      <li><span class="checkbox-box"></span>Go to an OH Event</li>
      <li><span class="checkbox-box"></span>Go to some West End Plays</li>
      <li><span class="checkbox-box"></span>Watch a match at Twickenham</li>
      <li><span class="checkbox-box"></span>Go to some music concerts</li>
      <li><span class="checkbox-box"></span>Van Tour the North Coast 500</li>
      <li><span class="checkbox-box"></span>Ski in the Alps from a Van</li>
    </ul>
  </div>

  <div class="bucket-section">
    <h3 class="bucket-subtitle">Personal Bucket List</h3>
    <ul class="clean-bucket-list">
      <li><span class="checkbox-box"></span>Paint the outside of the house</li>
      <li><span class="checkbox-box"></span>Complete house window renovations</li>
      <li><span class="checkbox-box"></span>Buy a campervan</li>
      <li><span class="checkbox-box"></span>Join a cycle club</li>
      <li><span class="checkbox-box"></span>Improve at windsurfing (waterstarts)</li>
      <li><span class="checkbox-box"></span>Pay off the mortgage</li>
      <li class="completed"><span class="checkbox-box"></span>Drop from 105kg to 95kg</li>
    </ul>
  </div>
</div>

<style>
  .bucket-list-container {
    padding: 10px 5px;
    font-family: 'Lora', Georgia, serif;
    color: #3c3c33;
  }
  .bucket-section {
    margin-bottom: 35px;
  }
  .bucket-subtitle {
    font-family: 'Montserrat', sans-serif;
    font-size: 16px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    color: #111111;
    margin-bottom: 18px;
    border-bottom: 2px solid #eef0ee;
    padding-bottom: 8px;
  }
  .clean-bucket-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .clean-bucket-list li {
    display: flex;
    align-items: flex-start;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 12px;
    color: #444444;
  }
  .checkbox-box {
    display: inline-block;
    width: 18px;
    height: 18px;
    border: 2px solid #a0a4a0;
    border-radius: 3px;
    margin-right: 12px;
    margin-top: 3px;
    flex-shrink: 0;
    background-color: #ffffff;
    position: relative;
    transition: all 0.2s ease;
  }
  .clean-bucket-list li:hover .checkbox-box {
    border-color: #7f9c90;
    background-color: #f8faf8;
  }
  .clean-bucket-list li.completed {
    color: #999999;
    text-decoration: line-through;
  }
  .clean-bucket-list li.completed .checkbox-box {
    border-color: #7f9c90;
    background-color: #7f9c90;
  }
  .clean-bucket-list li.completed .checkbox-box::after {
    content: '';
    position: absolute;
    left: 4px;
    top: 1px;
    width: 5px;
    height: 9px;
    border: solid #ffffff;
    border-width: 0 2px 2px 0;
    transform: rotate(45deg);
  }
</style>
