// var modal = document.getElementById("project-modal");
// var close_modal = modal.querySelector('.close-modal-project')
// var bg_modal = modal.querySelector('.bg-modal-project')
// document.querySelectorAll('.js-project').forEach(d => d.addEventListener("click", (event) => {
//     modal.style.display = "flex";
// }))

// close_modal.addEventListener('click', function (){
//     modal.style.display = "none";
// })

// bg_modal.addEventListener('click', function (){
//     modal.style.display = "none";
// })

// Get all elements with the class "js-project"
var triggers = document.querySelectorAll(".js-project");

// Attach click event listeners to each trigger
triggers.forEach(function (trigger) {
  trigger.addEventListener("click", function (event) {
    var modalId = trigger.getAttribute("data-modal");
    var modal = document.getElementById(modalId);

    if (modal) {
      modal.style.display = "flex";
    }
  });
});

// Add event listeners to close buttons and background
var modals = document.querySelectorAll(".modal");

modals.forEach(function (modal) {
  var close_modal = modal.querySelector(".close-modal-project");
  var bg_modal = modal.querySelector(".bg-modal-project");

  close_modal.addEventListener("click", function () {
    modal.style.display = "none";
  });

  bg_modal.addEventListener("click", function () {
    modal.style.display = "none";
  });
});
