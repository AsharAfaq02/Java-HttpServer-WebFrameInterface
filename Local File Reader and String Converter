import java.io.IOException;
import java.nio.file.Files;
import java.nio.file.Paths;
public class fileOpener  
{    
    public static String htmlFile(String filePath) 
    {
        String content = "";
        	try
        		{
            content = new String ( Files.readAllBytes( Paths.get(filePath) ) );
        	} 
        	catch (IOException e) 
        		{
            e.printStackTrace();
        	}
        return content;
    }
}
