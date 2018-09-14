//Declare nameInt Array	
				int nameInt [] = {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};
			
			//Insert Answers into nameInt Array
				for(int x = 0; x < 30; x++) {
					int result = Integer.parseInt(contents[x+2]);
					nameInt[x] = result;
					System.out.println(nameInt[x]);
