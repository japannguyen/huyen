<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Gửi em!</title>
</head>

<body>
  <section>
    <div class="box">
      <div class="items"></div>
    </div>
  </section>
</body>
<script>
  let sectionSpan = document.querySelector("section");
  for (let i = 0; i < 630; i++) {
    let span = document.createElement("span");
    sectionSpan.appendChild(span)
  }
  var span = document.querySelectorAll("span");
  span.forEach(function (item) {
    item.addEventListener("click", () => {
      item.classList.toggle("active")
    })
  })
  let items = document.querySelector(".items")
  for (let j = 0; j<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Gửi em!</title>
</head>

<body>
  <section>
    <div class="box">
      <div class="items"></div>
    </div>
  </section>
</body>
<script>
  let sectionSpan = document.querySelector("section");
  for (let i = 0; i < 630; i++) {
    let span = document.createElement("span");
    sectionSpan.appendChild(span)
  }
  var span = document.querySelectorAll("span");
  span.forEach(function (item) {
    item.addEventListener("click", () => {
      item.classList.toggle("active")
    })
  })
  let items = document.querySelector(".items")
  for (let j = 0; j < 63; j++) {
    let div = document.createElement("div")
    div.classList.add("item")
    items.appendChild(div)
  }
</script>

</html> < 63; j++) {
    let div = document.createElement("div")
    div.classList.add("item")
    items.appendChild(div)
  }
</script>

</html>

