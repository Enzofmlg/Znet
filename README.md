  <div class="container">
    <div align="center">
      <img src="src/assets/for_readme/logo ZNET.png" alt="Z Net Logo">
    </div>
    <h2 align="center">The Utility Knife of Networking</h2>
    <div>
      <h2>Description:</h2>
      <p>Built to replace Netcat, Z Net is a personal and simple (but powerful) tool designed for reading and sending data over network connections, utilizing the TCP or UDP protocol.</p>
    </div>
    <a>[ Project Archived ]</a>
    <h2>Features</h2>
    <ul>
       <li><strong>Alpha-version: 1.0</strong></li>
       <li><strong>Last-version:</strong> It was build in version 3 of python. </li>
      <li><strong>Command Execution:</strong> It can execute commands specified via the -e or --execute option. This allows the tool to run commands on the target system.</li>
      <li><strong>File Upload:</strong> It can upload files to the target system using the -u or --upload option. This feature enables transferring files between the local and remote machines.</li>  
      <li><strong>Command Shell:</strong> It provides a command shell functionality when the -c or --command option is used. This allows interactive command execution on the target system.</li>  
      <li><strong>Listening Mode:</strong> It can act as a server and listen for incoming connections with the -l or --listen option. This allows it to accept connections from other systems.</li>  
      <li><strong>Port and IP Configuration:</strong> It allows specifying the port to connect or listen on via the -p or --port option, and the target IP address via the -t or --target option.</li>  
      <li><strong>Interactive Communication:</strong> It supports interactive communication between the client and server, allowing the exchange of data back and forth.</li>  
      <li><strong>Error Handling:</strong>It includes basic error handling, such as handling exceptions during command execution and closing sockets gracefully upon termination.</li>
    </ul>
    <h2>Installation - Linux</h2>
    <ol>
      <li>Clone the repository from GitHub: <code>git clone https://github.com/znet/znet.git</code></li>
      <li>Navigate to the project directory: <code>cd znet</code></li>
      <li>Install dependencies: <code>sudo apt-get install python3</code></li>
      <li>Run Z Net: <code>python znet --help</code></li>
    </ol>
  </div>
</body>
</html>
