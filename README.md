# https-nodeJs

To generate a self-signed certificate, run this command (Linux)<br>
  <ul>
    <li>openssl genrsa -out key.pem</li>
    <li>openssl req -new -key key.pem -out csr.pem</li>
    <li>openssl x509 -req -days 9999 -in csr.pem -signkey key.pem -out cert.pem</li>
    <li>rm csr.pem</li>
  </ul>
