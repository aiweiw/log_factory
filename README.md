log_factory is a wrapper for python logging.

Example：

from log_factory import FinalLogger

final_log = FinalLogger('final_logger.log')

final_log.info('test: %d, %s', 1, '2')


