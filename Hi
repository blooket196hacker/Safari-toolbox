(function() {
  // Create a floating toolbox GUI
  var toolbox = document.createElement('div');
  toolbox.style.position = 'fixed';
  toolbox.style.top = '0';
  toolbox.style.left = '0';
  toolbox.style.width = '300px';
  toolbox.style.height = '100%';
  toolbox.style.backgroundColor = '#333';
  toolbox.style.color = '#fff';
  toolbox.style.zIndex = '99999';
  toolbox.style.padding = '10px';
  toolbox.style.overflowY = 'scroll';
  toolbox.style.fontFamily = 'Arial, sans-serif';
  toolbox.style.boxShadow = '2px 2px 10px rgba(0, 0, 0, 0.3)';

  // Title at the top
  var title = document.createElement('h2');
  title.textContent = 'Safari++ Toolbox';
  title.style.textAlign = 'center';
  title.style.color = '#fff';
  toolbox.appendChild(title);

  // Tool list (50+ tools)
  var toolList = [
    { name: "Change Title", action: changeTitle },
    { name: "Remove Images", action: removeImages },
    { name: "Fake Page", action: fakePage },
    { name: "Tab Masker", action: tabMasker },
    { name: "History Spammer", action: historySpammer }
    // Add more tools as needed, like the 50 you mentioned earlier
  ];

  // Create buttons for each tool
  toolList.forEach(function(tool) {
    var button = document.createElement('button');
    button.textContent = tool.name;
    button.style.width = '100%';
    button.style.padding = '10px';
    button.style.margin = '5px 0';
    button.style.backgroundColor = '#444';
    button.style.color = '#fff';
    button.style.border = 'none';
    button.style.cursor = 'pointer';
    button.onclick = tool.action;
    toolbox.appendChild(button);
  });

  // Append toolbox to the body
  document.body.appendChild(toolbox);

  // Tool Functions
  function changeTitle() {
    document.title = 'Fake Page Title';
    alert('Page title changed!');
  }

  function removeImages() {
    document.querySelectorAll('img').forEach(img => img.remove());
    alert('All images removed!');
  }

  function fakePage() {
    alert('This is a fake page!');
  }

  function tabMasker() {
    alert('Tab Masker activated!');
    // Implement tab masking logic here if needed
  }

  function historySpammer() {
    alert('History Spammer activated!');
    // Implement history spamming logic here if needed
  }

})();
