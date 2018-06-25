<template>
  <div>

    <v-parallax src="static/bkrnd.png" height="680">
      
    </v-parallax>

    <v-container fill-height>
      <v-layout row wrap>
        <v-flex xs12 text-xs-center>
          <h1>What we do?</h1>
          <v-divider></v-divider>
        </v-flex>
        <v-flex xs12 sm4 class="pa-3">
          <v-card class="white black--text">
            <v-card-title>
              <div>
                <h2 class="primary--text text-xs-center">Fighting Gov't corruption</h2>
                <hr class="mt-2 mb-2">
                <p>Red Security gathers and exposes information on the curruption, manipulation, and spying by governments across the world.</p>
              </div>
            </v-card-title>
          </v-card>
        </v-flex>
        <v-flex xs12 sm4 class="pa-3">
          <v-card class="white black--text">
            <v-card-title>
              <div>
                <h2 class="primary--text text-xs-center">Pedophile 'Hunting'</h2>
                <hr class="mt-2 mb-2">
                <p>Red Security helps fight crime and online child predetors by luring and investigating them and reporting criminal activities, addresses, websites and more.</p>
              </div>
            </v-card-title>
          </v-card>
        </v-flex>
        <v-flex xs12 sm4 class="pa-3">
          <v-card class="white black--text">
            <v-card-title>
              <div>
                <h2 class="primary--text text-xs-center">News</h2>
                <hr class="mt-2 mb-2">
                <p>Red Security hopes to eventually spread relevant news, tutorials, and more about current events, technology, and activism through our developing news division Cerberus Bye News.</p>
              </div>
            </v-card-title>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>

    <v-parallax src="static/bkrnd.png" height="600">
      <v-layout row wrap align-center justify-center>
        <v-flex xs12 sm6>
          <v-card>
            <v-layout row wrap>
              <v-flex xs12 text-xs-center>
                <h1 class="pa-2">Groups</h1>
                <hr class="mb-2">
              </v-flex>
              <v-flex xs12 sm6 class="pa-2">
                <v-card class="white black--text">
                  <v-card-media src="static/enrs.jpg" height="200px"></v-card-media>
                  <hr class="red">
                  <v-card-title>
                    <h4>English Red Sec</h4>
                    <p>Red Security's English Division activities include Anti-Pedophilia and Anti-Extremism operations. It also runs the Cerberus Byte News and Tutorials website.</p>
                  </v-card-title>
                </v-card>
              </v-flex>
              <v-flex xs12 sm6 class="pa-2">
                <v-card class="white black--text">
                  <v-card-media src="static/brrs.png" height="200px"></v-card-media>
                  <hr class="red">
                  <v-card-title>
                    <h4>Portuguese Red Sec</h4>
                    <p>Red Security's Portuguese Division's activities focus on gathering and spreading information on the corruption and manipulation done by the Brazilian gov't and military.</p>
                  </v-card-title>
                </v-card>
              </v-flex>
            </v-layout>
          </v-card>
        </v-flex>
      </v-layout>
    </v-parallax>

    <v-container>
       <v-layout row wrap>
        <v-flex xs12 text-xs-center>
          <h1>News</h1>
          <v-divider class="mb-3"></v-divider>
        </v-flex>
        <v-flex xs12>
          <a class="twitter-timeline" data-height="500" data-theme="" data-link-color="#D32F2F" href="https://twitter.com/CerberusByte?ref_src=twsrc%5Etfw">Tweets by CerberusByte</a>
        </v-flex>
       </v-layout>
    </v-container>

    <v-parallax src="static/bkrnd.png" height="600">
      <v-layout row wrap align-center justify-center>
        <v-flex xs12 sm6>
          <v-card>
            <v-layout row wrap>
              <v-flex xs12 text-xs-center>
                <h1 class="pa-2">Donate or visit our Shop</h1>
                <hr class="mb-2">
              </v-flex>
              <v-flex xs12 sm6 class="pa-2">
                <v-card class="white black--text">
                  <hr class="red">
                  <v-card-title>
                    <h2>Donate</h2>
                    <p>Donate today to support our operations to end child exploitation, political corruption and manipulation and more, around the world. Donations accepted though PayPal, BitCoin or Patreon</p>
                    <v-layout row wrap>
                      <v-flex xs12 sm4 text-xs-center><v-btn flat style="color: #f96854"> Patreon</v-btn></v-flex>
                      <v-flex xs12 sm4 text-xs-center><v-btn flat style="color: #f7931a"> Bitcoin</v-btn></v-flex>
                      <v-flex xs12 sm4 text-xs-center><v-btn flat style="color: #009cde"> Paypal</v-btn></v-flex>
                    </v-layout>
                  </v-card-title>
                </v-card>
              </v-flex>
              <v-flex xs12 sm6 class="pa-2">
                <v-card class="white black--text">
                  <hr class="red">
                  <v-card-title>
                    <h2>Shop</h2>
                    <p>Please Visit our shop for some super cool Pullovers, T-shirt and accessoiares :D</p>
                    <v-layout row wrap>
                      <v-flex xs12 text-xs-right>
                        <v-btn large class="primary">Visit Our Shop</v-btn>
                      </v-flex>
                    </v-layout>
                  </v-card-title>
                </v-card>
              </v-flex>
            </v-layout>
          </v-card>
        </v-flex>
      </v-layout>
    </v-parallax>

    <v-container>
      <v-layout row wrap>
        <v-flex xs12 text-xs-center>
          <h1>Contact</h1>
          <v-divider class="mb-3"></v-divider>
        </v-flex>
        
      </v-layout>
    </v-container>

  </div>
</template>