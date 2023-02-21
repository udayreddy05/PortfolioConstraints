---

| Script                                                     | Purpose                                                                                                  |
| ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `sherpa_BBDL_put_request.txt`                              | Put request (copy to client)                                                                             |
| `sherpa_BBDL_get_request.txt`                              | Get request (extract from client)                                                                        |
| `01_daily_mkt_data_processing_and_db_upload_autorun`       | This is a daily BAU script runs using Synology scheduler to                                              |
| `03_market_data_full_update_for_tickers with corp actions` | This script used to do the full update the market data for                                               |
| `03_market_data_upload_new_tickers`                        | This script used to process the data of new tickers and upload into the database.                        |
| `mkt_data_from_db_using_NAS_DB_v2.py`                      | With the market data input parameters, this script will extract the market data from database(cloud/NAS) |
