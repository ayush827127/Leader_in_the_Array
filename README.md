# Leader_in_the_Array
Find the The Leader in the given array Using Java


Solution :-

	public int leader_of_the_array(int[] arr) {
		int lead = arr[0];
		
		for(int i = 0; i < arr.length - 1; i++) {
			if(lead < arr[i+1]) {
				lead = arr[i+1];
			}
		}
		return lead;
	}


