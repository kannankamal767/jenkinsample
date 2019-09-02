    public class pageopened{
    	public static void main(String[] args){
          driver.manage().window().maximize();
	  driver.get("https://www.bharatmatrimony.com/");
	  JavascriptExecutor js=(JavascriptExecutor)driver;
	  js.executeScript("window.scrollBy(0,1400)");
	  Thread.sleep(5000);
	  js.executeScript("window.scrollBy(0,-1400)");
	  
	}
	}
