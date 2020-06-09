# testing with mocha (javascript)

* https://mochajs.org/#installation

## Part 1
* https://codeburst.io/how-to-test-javascript-with-mocha-the-basics-80132324752e
Testing the Mocha install

1. `npm install mocha -g`  (if you use -g can run as `mocha`)
2. `mkdir trymocha; cd trymocha;npm init`
3. `npm test`    see [test.js.setup](test.js.setup)
    ```
	tricia@acerubuntu1804:~/js320/trymocha$ npm test

	> trymocha@1.0.0 test /home/tricia/js320/trymocha
	> mocha



	  Array
	    #indexOf()
	      ✓ should return -1 when the value is not present

	  Math
	    ✓ should test if 3*3 = 9
	    ✓ should test true if (3-4)*8 = -8


	  3 passing (14ms)

	tricia@acerubuntu1804:~/js320/trymocha$
    ```
## Part 2
* https://codeburst.io/how-to-test-javascript-with-mocha-part-2-2d83fcb6101a

Testing [app.js](app.js)
1. `npm test`    see [test.js](test.js)
    ```
    > trymocha@1.0.0 test /home/tricia/js320/trymocha
    > mocha



      Temperature Conversion
        cToF
          ✓ should convert -40 celsius to -40 fahrenheit
          ✓ should convert 0 celsius to 32 fahrenheit
          ✓ should return undefined if no temperature is input
        fToC
          ✓ should convert -40 fahrenheit to -40 celsius
          ✓ should convert 32 fahrenheit to 0 celsius
          ✓ should return undefined if no temperature is input

      6 passing (16ms)

    ```

