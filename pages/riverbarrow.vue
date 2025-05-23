<template>
  <div>
    <app-masthead
      featuredImage="https://res.cloudinary.com/odriscolls/image/upload/q_auto,f_auto/v1584304563/river-barrow-header-large.jpg"></app-masthead>
    <div class="container">
      <div class="flex flex-wrap justify-between">
        <div class="w-full tracking-tight text-gray-600 md:w-9/20">
          <h1 class="title">
            <small>An Bhearu</small>
            River Barrow
          </h1>
          <p>
            The River Barrow, historically a significant highway, was developed as a commercial
            navigation in the mid seventeen hundred and Graignamanagh served as the main base for
            commercial barges operating on the river until barge traffic ceased in 1959.
          </p>
          <p class="mt-4">
            The River Barrow is a bustling, colorful navigation. The river runs for 192 km from its
            source in Glenbarrow in the Slieve Bloom Mountains in the midlands of Ireland to the
            sea. The Barrow has long been recognized as a unique area of great natural beauty with
            high amenity value, traversing the counties of Laois, Kildare, Carlow, Kilkenny and
            Wexford. The Barrow Navigation is the stretch of the River Barrow between Athy in Co.
            Kildare and St. Mullins in Co. Carlow. Above Athy, the Barrow Line of the Grand Canal
            links the Barrow Navigation to the main line of the Grand Canal at Lowtown in Co.
            Kildare. From there the Grand Canal crosses the country west to the River Shannon,
            Ireland's longest waterways network and east to Dublin.
          </p>
          <p class="mt-4">
            The Barrow Navigation is the stretch of the River Barrow between Athy in Co. Kildare and
            St. Mullins in Co. Carlow. Above Athy, the Barrow Line of the Grand Canal links the
            Barrow Navigation to the main line of the Grand Canal at Lowtown in Co. Kildare,
            facilitating access to Ireland's extensive waterways network.
          </p>
          <p class="mt-4">
            Traveling along the Barrow Line of the Grand Canal is a tranquil experience, with a
            wealth of waterway heritage and history to be enjoyed. The Barrow Navigation offers a
            different experience for the visitor being remarkably picturesque, with short man-made
            canal cuts bypassing shallow stretches of the river.
          </p>
        </div>
        <div class="w-full md:w-9/20 md:-mt-32">
          <img
            src="https://res.cloudinary.com/odriscolls/image/upload/q_auto,f_auto/v1584304554/graig-air_x2.jpg"
            alt="A view of the River Barrow with Graiguenamanagh and Tinniahinch on either side"
            class="my-12 md:mb-16" />
          <p>
            It is a bustling river with a wealth of activities for visitors to enjoy — from walking
            or cycling along the unspoiled Barrow Towpath to spotting herons and kingfishers along
            its banks and engaging in fishing, boating, and canoeing. The River Barrow is navigable
            south to Saint Mullins where it merges with tidal waters, linking with the River Nore
            and leading to New Ross and the open sea. Northwards, it connects with the Grand Canal
            at Lowtown, Co. Kildare.
          </p>
        </div>
      </div>
    </div>

    <div class="container my-16">
      <div class="flex flex-wrap justify-between">
        <div class="w-full">
          <h2 class="title">Exploring the River Barrow</h2>
          <p>
            Exploring the River Barrow offers visitors an opportunity to immerse themselves in the
            stunning landscapes and rich biodiversity. As you stroll along the banks or navigate the
            waters, you may encounter an array of flora and fauna that make this river one of
            Ireland's most cherished natural assets.
          </p>
          <p class="mt-4">
            Local fishing competitions and canoeing events are frequently held on the River Barrow,
            promoting community engagement and conservation of this remarkable waterway. Whether
            you're a seasoned angler or a beginner, the diverse aquatic life along the river offers
            an exciting experience.
          </p>
        </div>
      </div>
    </div>

    <div class="container">
      <img
        src="https://res.cloudinary.com/odriscolls/image/upload/v1584304558/bridge-line-art.png"
        alt="Digital drawing of the Graignamangh bridge by Scott Kennedy"
        class="my-16 origin-top-right transform scale-110" />

      <div class="flex flex-wrap justify-between">
        <div class="w-full md:w-9/20">
          <h2 class="title">George Semple Bridge</h2>
          <p>
            A stone bridge existed on the site of the present bridge before 1641. Following their
            retreat to Graignamanagh after the battle of Ballinvegga in 1643, general Thomas
            Preston's Confederate troops demolished part of that bridge to prevent the English from
            crossing the river into Graigue, which the Confederate Army was defending.
          </p>
        </div>
        <div class="w-full mt-4 md:w-9/20">
          <p>
            Some 120 years later, the “great flood” of 1763 probably destroyed the bridge. The
            present bridge, built in 1767, was built to the design of George Smith, a pupil of
            George Semple, though it has traditionally been attributed to the master himself, making
            it of national architectural importance.
          </p>
          <p class="mt-4">
            During the 1798 Rebellion, the Crown forces blew up the arch of the bridge nearest the
            County Carlow side of the River Barrow to prevent the Wexford rebels from entering
            County Kilkenny. In this way, they echoed the destruction of the previous bridge by the
            Confederate Army 145 years earlier.
          </p>
        </div>
      </div>
    </div>
    <!-- <image-gallery name="River Barrow" tag="riverbarrow" /> -->
    <insta-feed hashtag="riverbarrow" numberOfImages="32" />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'River Barrow | Village of the Monks',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'The River Barrow is a bustling, colorful navigation. The river runs for 192 km from its source in Glenbarrow in the Slieve Bloom Mountains in the midlands of Ireland to the sea. The Barrow has long been recognized as a unique area of great natural beauty with high amenity value, traversing the counties of Laois, Kildare, Carlow, Kilkenny and Wexford.',
        },
        {
          name: 'keywords',
          content:
            'Graiguenamanagh, Graignamanagh, river, barrow, abbey, Village, Monks, Wexford, Kilkenny, Carlow, Kildare, navigation, Town, Books, Pubs, Ireland, Duiske, Slieve, Bloom, Mountains',
        },
      ],
    };
  },
};
</script>
