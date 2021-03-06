# gcloud --help
NAME
    gcloud - manage Google Cloud Platform resources and developer workflow

SYNOPSIS
    gcloud GROUP | COMMAND [--account=ACCOUNT] [--configuration=CONFIGURATION]
        [--flatten=[KEY,...]] [--format=FORMAT] [--help] [--project=PROJECT_ID]
        [--quiet, -q] [--verbosity=VERBOSITY; default="warning"] [-h]
        [--version, -v] [--log-http] [--trace-token=TRACE_TOKEN]
        [--no-user-output-enabled]

DESCRIPTION
    The gcloud CLI manages authentication, local configuration, developer
    workflow, and interactions with the Google Cloud Platform APIs.

GCLOUD WIDE FLAGS
     --account=ACCOUNT
        Google Cloud Platform user account to use for invocation. Overrides the
        default core/account property value for this command invocation.

     --configuration=CONFIGURATION
        The configuration to use for this command invocation. For more
        information on how to use configurations, run: gcloud topic
        configurations. You can also use the [CLOUDSDK_ACTIVE_CONFIG_NAME]
        environment variable to set the equivalent of this flag for a terminal
        session.

     --flatten=[KEY,...]
        Flatten name[] output resource slices in KEY into separate records for
        each item in each slice. Multiple keys and slices may be specified.
        This also flattens keys for --format and --filter. For example,
        --flatten=abc.def[] flattens abc.def[].ghi references to abc.def.ghi. A
        resource record containing abc.def[] with N elements will expand to N
        records in the flattened output. This flag interacts with other flags
        that are applied in this order: --flatten, --sort-by, --filter,
        --limit.

     --format=FORMAT
        Sets the format for printing command output resources. The default is a
        command-specific human-friendly output format. The supported formats
        are: config, csv, default, diff, disable, flattened, get, json, list,
        multi, none, object, table, text, value, yaml. For more details run $
        gcloud topic formats.

     --help
        Display detailed help.

     --project=PROJECT_ID
        The Google Cloud Platform project name to use for this invocation. If
        omitted then the current project is assumed. Overrides the default
        core/project property value for this command invocation.

     --quiet, -q
        Disable all interactive prompts when running gcloud commands. If input
        is required, defaults will be used, or an error will be raised.
        Overrides the default core/disable_prompts property value for this
        command invocation. Must be used at the beginning of commands. This is
        equivalent to setting the environment variable
        CLOUDSDK_CORE_DISABLE_PROMPTS to 1.

     --verbosity=VERBOSITY; default="warning"
        Override the default verbosity for this command. VERBOSITY must be one
        of: debug, info, warning, error, critical, none.

     -h
        Print a summary help and exit.

     --version, -v
        Print version information and exit. This flag is only available at the
        global level.

OTHER FLAGS
     --log-http
        Log all HTTP server requests and responses to stderr. Overrides the
        default core/log_http property value for this command invocation.

     --trace-token=TRACE_TOKEN
        Token used to route traces of service requests for investigation of
        issues. Overrides the default core/trace_token property value for this
        command invocation.

     --user-output-enabled
        Print user intended output to the console. Overrides the default
        core/user_output_enabled property value for this command invocation.
        Use --no-user-output-enabled to disable.

GROUPS
    GROUP is one of the following:

     app
        Manage your App Engine deployments.

     auth
        Manage oauth2 credentials for the Google Cloud SDK.

     components
        List, install, update, or remove Google Cloud SDK components.

     compute
        Create and manipulate Google Compute Engine resources.

     config
        View and edit Cloud SDK properties.

     container
        Deploy and manage clusters of machines for running containers.

     dataflow
        Manage Google Cloud Dataflow jobs.

     dataproc
        Create and manage Google Cloud Dataproc clusters and jobs.

     datastore
        Manage your Cloud Datastore indexes.

     debug
        Commands for interacting with the Cloud Debugger.

     deployment-manager
        Manage deployments of cloud resources.

     dns
        Manage your Cloud DNS managed-zones and record-sets.

     domains
        Manage domains for your Google Cloud projects.

     firebase
        Work with Google Firebase.

     iam
        Manage IAM service accounts and keys.

     kms
        Manage cryptographic keys in the cloud.

     logging
        Manage Stackdriver Logging.

     ml
        Use Google Cloud machine learning capabilities.

     ml-engine
        Manage Cloud ML Engine jobs and models.

     organizations
        Create and manage Google Cloud Platform Organizations.

     projects
        Create and manage project access policies.

     service-management
        Create, enable and manage API services.

     source
        Cloud git repository commands.

     spanner
        Command groups for Cloud Spanner.

     sql
        Manage Cloud SQL databases.

     topic
        gcloud supplementary help.

COMMANDS
    COMMAND is one of the following:

     docker
        Provides the docker CLI access to the Google Container Registry.

     feedback
        Provide feedback to the Google Cloud SDK team.

     help
        Prints detailed help messages for the specified commands.

     info
        Display information about the current gcloud environment.

     init
        Initialize or reinitialize gcloud.

     version
        Print version information for Cloud SDK components.