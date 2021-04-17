public static void main( String[] args ) {

    int n;
    Random r = new Random();

    for ( int i = 0; i < 10; i++ ) {
        n = r.nextInt( 6 ) + 1;
        System.out.println( "Sorteou: " + n );
    }

    // ou...
    for ( int i = 0; i < 10; i++ ) {
        n = (int) ( Math.random() * 6 ) + 1;
        System.out.println( "Sorteou: " + n );
    }

}
