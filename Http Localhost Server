import java.io.IOException;
import java.net.InetSocketAddress;
import com.sun.net.httpserver.HttpServer;

public class LocalhostServer {
public static void main(String[] args) throws IOException {
	
	HttpServer server = HttpServer.create(new InetSocketAddress(**PORT**), 0);
     com.sun.net.httpserver.HttpContext context = server.createContext("/");
     context.setHandler(LocalhostServer::handleRequest);
     server.start();
     }

public static void handleRequest(HttpExchange exchange) throws IOException {
			  String filePath = "PATHTOFILE";
					exchange.sendResponseHeaders(200, fileOpener.htmlFile(filePath).getBytes().length);//response code and length
			      OutputStream os = exchange.getResponseBody();
			      os.write(fileOpener.htmlFile(filePath).getBytes());
			      os.close();

     }
}
