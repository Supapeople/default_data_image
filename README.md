<h2>Configuration Details</h2>

<p>For each game, a default JSON with some basic attributes need to be configured. For example: <code>hoc_data_prod.json</code> for Hunters on Chain. This shall be used in the case when <code>Opensea</code> doesn't have attributes data yet.</p>

<p>Similarly, we have JSON for looking up which data is required for a particular collection. We have that data configured against <code>collectionId</code> and <code>contractAddress</code>. Inside the sub-JSON, we have the original <code>tokenURI</code> (without the <code>tokenId</code> suffix). 
  This will be used for looking in case of any failure. Refer <code>attribute_data_mapping_prod.json</code></p>
