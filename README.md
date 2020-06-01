# localhost-Python
#localhost in python


from http.server import HTTPServer, CGIHTTPRequestHandler
server_data = ("localhost", 8080)# can vibrati another host
server = HTTPServer(server_data, CGIHTTPRequestHandler)
server.serve_forever()
