public class LED_Lamp {

	private LED red, green, blue;

	// Instance 3 LED
	public LED_Lamp() {
		red = new LED("red");
		green = new LED("green");
		blue = new LED("blue");
	}

	public boolean showLight(int lightIdx) {
		// Turn off any possible "on" LED
		if (red.isLEDOn()) red.turnOff();
		if (green.isLEDOn()) green.turnOff();
		if (blue.isLEDOn()) blue.turnOff();

		switch (lightIdx) {
			case 0:
				red.turnOn();
				System.out.println("Light is now " + red.getColor());
				return true;
			case 1:
				green.turnOn();
				System.out.println("Light is now " + green.getColor());				
				return true;
			case 2:
				blue.turnOn();
				System.out.println("Light is now " + blue.getColor());				
				return true;
			default:
				System.out.println("Error!! Expects 0, 1 or 2.");
				return false;
		}
	}
}
